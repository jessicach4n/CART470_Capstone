# Week 4 - Testing JSON structure and the JSON-generating form
## Continuing development

### Uncertainties
- If each student had their own forked client, it would not be convenient for each team's musical piece to be queued and played one after another. The server would need the URLs of each client to be added to the allowed URLs.
  - We decided to keep all student files in a single repository rather than allowing students to fork the client. This means the idea for each team to be able to modify their own UI will not be implemented.

### Meeting with Gabriel
Some pointers he gave us:
- Look into MQTT instead of using Render
- Think of a calibration system for testing volume (e.g., a beep test)
- The conductor view can schedule the different pieces to play from all the teams
- Look into preventing the phone from going into sleep mode (e.g., playing a one-pixel video)
- Think of how to visually represent the score in the conductor view
- Visualize which sounds each group of phones is playing by visualizing the effects (e.g., fade in and out, etc.)
- Other effects: controlling the overall sound level, controlling fade in and out, controlling the drift, etc. (Drift: two phones play the same sound at different speeds)
- Use the Audio API and audio context

### JSON structure
This is the first version of the JSON structure:
```
{
  "title": "Test Piece",
  "sounds": {
    "test": "audio/test.wav",
    "belly": "audio/belly.wav"
  },
  "groups": {
    "0": {
      "effects": [],
      "events": [
        { "at": 0, "play": "test" },
        { "at": 0, "play": "belly" },
        { "at": 0, "set": "gain", "value": 0 },
        { "at": 0, "ramp": "gain", "to": 1, "over": 4 }
      ]
    },
    "1": {
      "effects": [
        { "id": "filter", "type": "lowpass", "frequency": 500 }
      ],
      "events": [
        { "at": 5, "play": "belly" },
        { "at": 10, "ramp": "filter.frequency", "to": 3000, "over": 8 }
      ]
    }
  }
}
```
It was discussed that it might not be a good idea for students to edit the JSON file directly. Therefore, we are implementing a page with a form that will help students generate the JSON more intuitively.

### Research
I looked into MQTT, and it could be a valid option for implementing communication between devices. However, due to the short deadline, we decided it is best to stick with technologies we are familiar with. Furthermore, the demo works on Render, so we would like to continue using Render and focus on completing other tasks.
