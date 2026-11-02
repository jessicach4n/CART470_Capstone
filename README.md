# Week 6 - The Curve Ball

## Meeting with Gabriel
We met with Gabriel and showed him what we have successfully implemented so far, which included all the minimum requirements he wanted for the initially set deadline of November 3rd. 

We were able to show him a working version of the JSON generator, the conductor view, and the phone view. 
[Our application](https://jessicach4n.github.io/Distributed_Listening/) included the following features:
- The JSON generator allows the user to upload audio files and fill out the fields in the form. It then generates a JSON file that contains the information from the form and the audio files all packaged in a single zip file. This structure would allow us to easily upload the folders to the repository and have the application read the files properly.
- The conductor view allows the user to select the piece to play, see the list of groups and the number of phones connected in each group, as well as display a QR code for phones to scan and connect to the application.
- The phone view allows the user to connect to the application by scanning the QR code, join a group and be notified when the conductor starts the piece of the audio assigned to their group ID.
<video src="demo.mov" controls></video>


## Gabriel's Feedback and Surprise Curve Ball
Gabriel seemed happy with our progress and the features we implemented, but surprised us with a fully developed version of the application that he had been working on since September. He has already implemented the views we have been working on, as well as additional features that we have not yet implemented, such as a visual representation of the audio in a waveform, a reactive phone view changes based on the audio being played similar to what we hoped to acheive with p5, latency compensation and live adjustement of the speed and volume of the audio, dark and light modes, and more. 

We also learned that this will be the version that he plans to use in his class, which affects our initial plan to do user testing in the coming weeks with his students on our version of the application.

Given this new information, we will have to fork his version of the application to add features that he wants to implement. This includes:
- Effects and filters for the audio
- Fetching audio files from a external source instead uploading them to the application
- Implementing a form generator like ours

Eamon worked on these features this week and met with Gabriel to get his feedback on the implementation. The features were approved by Gabriel and he was happy to see the changes Eamon made to the application.

## Communication and Collaboration
We felt that there was a miscommunication between us and Gabriel regarding the expectations of the project. We were under the impression that we were working on implementing the base of the application and that the additional features would be implemented later. To move forward, we will have to rethink the roles of the team and how we can contribute to his project while maintaining our own version. 

Despite this, we understand that Gabriel needs a solid version that he can rely on for his class. What we have learned from building our own version isn't wasted.

## Next Steps
Since we would like to continue advancing our project, we will continue to work on it as planned, but also focus on helping Gabriel with his version of the application after he gets feedback from his students. Since we will not directly do user testing, Gabriel will do the demo with his students and he will give us their feedback. We will then use this feedback to improve both application.

We also are working on the miderm presentation and will be preparing a demo of our application to show the class. 

