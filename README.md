# emotion-recognition-app
Android App that helps children on the spectrum recognize emotions using the phones camera, face tracking, and machine learning

EXAMPLES:<br>
Greyscale camera footage             |  Bytearray footage
:-------------------------:|:-------------------------:
![](https://github.com/MaxHarlan206/emotion-recognition-app/blob/main/greyscale-phone-video.gif)  |  ![](https://github.com/MaxHarlan206/emotion-recognition-app/blob/main/gray-scale-bytearray.gif)

MOTIVATION:<br>
I have been having two recurring conversations lately with friends:
The first is how we think that not seeing enough strangers faces (due to masks) during early formative years might lead to an increased incedence of aspergers like symptoms. 
The second, similar conversation has been how the same is true of children who's parents just hand them an iPad to play on instead of spending quality social time with the poor kid. 
Regardless of if these ideas are true, existing children on the spectrum seem to be able to navigate relationships better after being taught how to read and respond to emotions. Even if this were not true; however, the technology behind such an app could act to augment the skills that the user is struggling with. It is in the spirit of bringing this practice from an isolated, classroom/online course like setting into more of a real world, real time application that I am making this app. 

DOCUMENTATION:<br>
Papers on emotion recognition training for kids on the spectrum:
* [Emotion recognition training in autism spectrum disorder: A systematic review of challenges related to generalizability](https://pubmed.ncbi.nlm.nih.gov/28394669/ "Emotion recognition training in autism spectrum disorder: A systematic review of challenges related to generalizability")
  * Shows the inconclusive nature of emotion recognition training and links out to 13 studies in that area. 
* [Can emotion recognition be taught to children with autism spectrum conditions?](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2781897/ "Can emotion recognition be taught to children with autism spectrum conditions?")
  * An interesting study which proposes that emotional recognition content be paired with content that children on the specrum typically enjoy (such as cars and machines) It also proposes a model of the nature of empathy and shows that emotional recognition was successfully trained in accordance with this model. 
* [Teaching Children with Autism Spectrum Disorder to Recognize and Express Emotion: A Review of the Literature](https://files.eric.ed.gov/fulltext/EJ1126647.pdf "Teaching Children with Autism Spectrum Disorder to Recognize and Express Emotion: A Review of the Literature")
  * An article which focuses on both the affective and cognitive aspects of emotional skills training which are needed. May serve as later inspiration for added features to the app. Additionally validates the pain point of difficulty translating learned skills in most software to real life, the core pain point I am building around.
* [Emotional development in autistic children](https://raisingchildren.net.au/autism/development/social-emotional-development/emotional-development-asd "Emotional development in autistic children")
  * Not a research paper but this blog article may provide an outline for a full spectrum solution to emotional skills  training for autistic children as a terminal point of this app.
  
Libraries used:
* Requests - used to get the webcam stream from a url
* OpenCV - for facial recognition and tracking 
* NumPy - to translate the camera feed into a byte array that can be processed by OpenCV

Special thanks: 
* [Prajjwal Pathak](https://github.com/pyGuru123)

