# Week 2 - Brainstorming
## Ideation
### Questions to ask the stakeholder
During class, we defined a set of questions we would like to ask Gabriel to help us understand the project better. These questions aim to define the scope of the project and the technical needs.
- Is there 1 controller for all the phones?
- What kind of control do you want?
- How do the phones/ audience participate (ex: device mouvement/position)?
- Up to how many phones?
- Is each phone a single specialization point?
- OSC? Or MCP?
- How do you plan to use this project for CART 346?
- Do the phones give feedback ( are they just output or input)?
- Do you want to join rooms, or use a QR code to the room or a QR code to the site?
- Server budget?
- What UI screens do you need?
- What is the source of the music?

### Resources
- [Client Brief](files/distributedListening_gabriel.pdf)
- [massMobile – an Audience Participation Framework](https://nime.org/proceedings/2012/nime2012_128.pdf)
- [Beatsync](https://github.com/freeman-jiang/beatsync)
- [Sparse’s Phone Orchestra Creates Symphonies Among Strangers](https://www.insomniac.com/magazine/sparses-phone-orchestra-creates-symphonies-among-strangers/)
- [Experiments with Google](https://experiments.withgoogle.com/experiments)

## Meeting with Gabriel
I was not able to attend the meeting with Gabriel, but I went through the [notes](files/meeting_notes_gabriel.md) my teammates took, and I included some comments to be discussed at our next meeting. The main points I gathered are:
- The project is a web app that allows the audience to use their phones as speakers to be part of an orchestra made of phones.
- We will focus on developing the web app with JavaScript, and it will be used as a base for students in his audio class to fork and adapt to their own projects.
- It does not need to have much interactivity regarding the UI; it will be used mostly as a tool to diffuse sound.
- Chrome is the preferred browser, but since we do not have control over the audience's phones, we will need to make sure it works on other browsers as well.
- We will need a server that can handle up to 50 connected phones at the same time and handle dispatching audio.
- He wants the audio to be minimally synchronized. I have a project that I previously worked on that we could adapt and use for this project. Link to the project: [Crosswalk_Sound_Sim_RAAMM](https://github.com/jessicach4n/Crosswalk_Sound_Sim_RAAMM)
- The web app will be accessed through a QR code. 

## Next Steps
- Write down a list of features that must be implemented for the project to be functional and have it approved by Gabriel.
- Build a skeleton of the web app with a basic UI and audio dispatching.
- Code the server that will handle connections and dispatch audio to the connected phones.
- Brainstorm whether we want to design a UI.
