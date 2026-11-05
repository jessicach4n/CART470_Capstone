# Week 8 - Post Midterm

## Meeting with Gabriel
We did not have a meeting with Gabriel as a team this week, but Eamon met with him to show the progress he made in adding some of the features Gabriel requested, such as fetching audio files from external sources, audio effects and implementing a form generator. 

Victoria and Eamon also assisted in Gabriel's demo of his application to his students. From what I gathered, the students did not have feedback on the application yet, because they spent the rest of the class trying to download Node.js and set up the application on their local machine. 
It is unclear to me why he decided to have the students set up the application locally since they apparently had a lot of trouble doing so. We are offering our help to Gabriel if he wants us to attend his classes to help the students set up, but nothing has been decided yet.

## Midterm Presentation
The presentation went well; most notably, we were able to test our version of the application with the 22 phones of the students in the class. The feedback was positive since it was a pretty seamless experience to join the session and play the piece. We were surprised by how well it performed with that many devices, and we were happy with how it sounded. We don't think it is necessary to implement the latency compensation feature since the experience was synchronous enough for the students to play together. Also, the latency that Gabriel adjusts for doesn't seem to go over 10ms at most, which is not noticeable.

## Next Steps
We discussed what we would like to present at the final presentation, and we have decided that we would like to focus on an exhibition-style presentation where we will perform one of our pieces with the students in class as participants with their phones.
Since that will be our end goal, we will focus on finishing features that students in our class will directly interact with, in other words, the phone interface. 

Since our JSON form generator won't be used in our use case and a copy of the feature is in progress in Gabriel's application, we may leave it as it is rather than trying to add CSS styling. We can use that energy to focus on the phone interface and the audio effects.

We discussed potentially making a p5 animation for each, so 5 different animations, that can then be associated with each group of phones. For example, if we have 5 groups of phones, each group can have a different animation that is triggered by the audio from the phones in that group. This will make the experience more visually engaging for the students.

Another thing we need to work on is preventing the phone from going to sleep while the application is running. We will look into ways to prevent this from happening, since it would be disruptive to the experience if a phone goes to sleep in the middle of a performance. Gabriel suggested playing a 1px video in the background to prevent the phone from going to sleep, but we will look into other options as well.

We also want to further develop the conductor interface and integrate more features, such as a waveform for the audio being played, kicking out phones from the session and finishing the CSS.

