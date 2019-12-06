# MCA

 <div class="menu">
    <a href="#">Week 1</a>
    <a href="">Week 2</a>
    <a href="">Week 3</a>
    <a href="https://rosieorourke.github.io/MCA-2019/Week_4/Week_4.html">Week 4</a>
    <a href="https://rosieorourke.github.io/MCA-2019/Week_5/Week_5.html">Week 5</a>
    <a href="https://rosieorourke.github.io/MCA-2019/Week_7/Week_7.html">Week 7</a>
    <a href="https://rosieorourke.github.io/MCA-2019/Week_8/Week_8.html">Week 8</a>
    <a href="https://rosieorourke.github.io/MCA-2019/Week_9/Week_9.html">Week 9</a>
    <a href="https://rosieorourke.github.io/MCA-2019/Week_10/Week_10.html">Week 10</a>
   </div>
<br></br>

<h2><b>Week 1</b><h2>
Task 1: Dataset Theme
 <br></br>
  The theme for my dataset is the French composer Erik Satie and his avant-garde and experimental style. Erik Satie was known as a 'unconventional' artist of the late 19th, early 20th century, and his compositions regularly disregarded 'traditional forms and tonal structures', making him a pioneer for modernism within music. I will focus on Satie's historical piece Gnossienne: No 1 which is a simple and understated piece of music, however it is filled with techniques, grace notes, and interesting minor melodies.
  
 
 
We were also asked to find 3 different sources of music data and consider the traits of each source. 
Spotify
<br></br>
<i>What type of music data is contained?</i>
An array of music data including artist, song title, album title and art, duration, date of release, record company, writers, producers,  monthly listeners, relates/similar artists. 

<i>How is the data presented?</i>
The data is presented in either playlists, albums, or singles. There is an option to present the data in alphabetical order, although this is only availble on computers/laptops. 

<i>What is unique or innovative about the dataset and the way it is presented?</i>
The dataset is presented on a consistent black background which gives the application a sleek design which is not used in other music apps. Spotify also creates unique playlists weekly for users. This contains recommendations from artists similar to the ones the user 


<b>Apple Music</b>







<h2><b>Week 2</b><h2>
This week we had the task of transcribing a piece of music onto MuseScore. We had to find the sheet music from IMSLP which is an extensive music library. Due to my previous experience studying music and using Scalar which is a similar program to MuseScore, I transcribed the piece and offered guidance to my peers. From a brief lesson on musical notes and their values, my peers were able to follow this process. 
I chose the piece Gymnopedie by Erik Satie due to it's simplicity, however this is still a classical piece of music so the piece still contained many interesting features that we could discuss. We successfully transcribed 8 bars within the time we had in the lab. 

For the individual lab task, we were asked to trancribe at least 10 bars of music and consequently upload this to github. 



<h2><b>Week 3</b></h2>
The group task for this week was to analyse an uncompressed music xml version of our transcribed music. I opened up the XML version in Notepad ++ and explored this version usefulness. 
<br></br>

<i>How are pitch, rhythm, and time represented in the XML file?</i>
These features are represented in a typical coding style with tags. The pitch tag contains two sub tags which is 'step' and 'octave' and occasionally the subtag 'alter', this is used for every single note that has been transcribed. The rhythm and time of the piece which is usually identified as a time signature features in the 'attributes' tag of the XML file. Furthermore the time signature is held in a 'time' tag which includes the direct tag of 'beats' which describes the number beats in a measure, and a 'beat-type' tag which describes the type of note present. Time is also represented in a unique way as the XML file describes the distance of the staff in millimetres instead of the actual duration which MuseScore presents.

<i>Is there data that is excluded from this encoding standard?</i>
XML does not include the dynamic changes such as the music getting louder or quieter in it's standard. As these are smaller details that are not necassary within a piece it is possible that the encoding standard doesn't know to represent these details in a code.   

<i>What are potential strengths and weaknesses of this approach?</i>
This approach is useful for someone who has limited musical knowledge as it explains what each note represents. For instance the XML version includes the tag 'sign' which explains the actual note type such as a G or an F, the 'line' tag then indicates which line of the staff this note appears on. This information is not presented in MuseScore as this is considered to be prior knowledge. An obvious weakness of this approach is that it does not play the audio of the piece, and it is difficult to imagine what the piece would sound like when reading numbers from a code. As each note has so many details attatched to it, the coding representation is also harder to follow compared to following the staff on the MuseScore version. The user has to scroll past thousands of lines of coding making it quite inefficent and time consuming.

