<!-- Converted from exported Google Docs html file to markdown with GPT-5.6 Luna -->

# Sept 21

## CART 470

* for the sound class (max)

* focusing more on sound design for **specific design**

  * **Comment:** What specific design?

* cool set up (old orchestra of ~ 50 speakers)

* design some sort of projecting the sounds within the orchestra speakers and making sequences of sound

* go into a certain venue, scan with the QR code and your phone becomes a speaker — you become another sensor

* you’re in charge of **specialization**

  * **Comment:** What do u mean by specialization?

* Concept for the sound design + series of sounds around that concept

* these sounds will be rendered into the phones (having the phones on the floor, for example)

* how the sounds will be rendered? - sequence w over time

* forest with cicada (example)

* we have to provide the **infrastructure**

  * **Comment:** Which includes what? We should write a clear list of expected features and have it approved by Gabriel early on to avoid surprises.

* procedural sound machine

* sound A will sound from 0 - 2min

* sound B will be from here to somewhere

* sending sound for one orbit or another but do not necessarily have an actual form

* **for starter - pool of 25 (divided by 5)**

  * **Comment:** As in 5 times the same output for 5 different outputs?

* no max (full JavaScript) - focus on the sound more than the max

* We’re the ones who are manipulating the code (?)

  * **Comment:** so we want an UI that lets you manipulate sound via code ?

* webpage loaded on audio assets

  * **Comment:** What does this mean? Do we need to store audio assets on the webpage?

* how are they making the sounds **sync together (about the same time)**

  * **Comment:** WebSocket for communication between devices and the server
  * **Comment:** See: https://github.com/jessicach4n/Crosswalk_Sound_Sim_RAAMM/blob/main/docs/js/sound-engine.js

* centralized application with server might be needed

* computecanada (???) - canada wide interconnected series of computer cluster (is used by concordia)

* phone is receiver (**no interaction**) - for the very first iteration

  * **Comment:** No UI at all? What about a page to sign in to a server room, or is the QR code unique to the room? Without any interaction, you can't play sounds from a browser, it will be blocked. Users have to click on the page in order for the sound to play, browser default behavior.
  * **Comment:** Also, for safety, having a QR code give you open access to the server room would be risky... It would be good to add a password for security.

* for now it’s just a speaker

* visual display (does not matter much)

* visual elements (that’s fine)

* hosted on a repo - different groups of sound class should be able to fork this and own their assets / sequence the sound

* sequencing of the sound - **what kind of structure**

  * **Comment:** what structure are we talking about ? is it like structure oh how the sound will play ? ToT?

* maybe astatic (?)

* **web app**

  * **Comment:** Will it be accessible on any browser on any type of device, or do we want to block anything that isn't a phone?

* **chrome for default**

  * **Comment:** We can test and develop it for Chrome, but it's not up to us whether the user will use Chrome. The user's default browser on their phone will open the link from the QR code.

* **audio api - pretty standard amongst certain browsers**

  * **Comment:** How do we plan to use the API?

* **portable web app that can be loaded onto you phone**

  * **Comment:** As long as you have a browser on the phone and internet, it will load. It is not going to be a native app, so it will not be downloadable and live on the phone as a native application.

* doesn’t work - web midi api

* providing js versions of those apps and people can actually focus on actual sound design

  * **Comment:** example pls QwQ i need clarificationo on this whole point
  * **Comment:** I think this is related to how he mentions that students will fork the repo to adapt to their project.

* more iteration

* start w same sound from computer and phone (**loading the audio assets** — web app)

  * **Comment:** Provided?

* activating them in synchronously

* run like a clock (eamon - yt video)

* modulos/random ??

* no need for perfection in syncing

* how are we going to instantiate web browser or different tabs of audio output > working with the machine in the room

  * **Comment:** Is one device supposed to open different tabs with different sounds? Does that mean scanning different QR codes? What is the machine in the room?

* loading the audio asset

* sequencing part