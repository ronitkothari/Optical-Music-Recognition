# Online Music Recognition

### Demo

[![Capriccio Demo Video](https://i.imgur.com/6qul89o.png)](https://youtu.be/AjBXx8oyJgM)


### OMR - What Is It?
Many of you may be familiar with optical character recognition (OCR), and the many companies that compete to do it the very best. Optical music recognition (OMR) is very similar, but far less studied and with equally fascinating applications.

The world of OMR is dominated by professors and post-graduate students, but by combining Kotlin, OpenCV, and a dash of ingenuity we were able to make it happen in just one weekend.

### How it Works
(1) SHEET MUSIC
Capriccio starts at the mobile level, where a user can either take a photo of their handwritten music directly from the app, or import it from their gallery.

(2) OPENCV
Taking the image, we use OpenCV to perform feature detection and clustering. We then progressively generate a MIDI file by determining the location of key musical objects and assigning them pitches.

(3) MIDI
Finally, we pipe our fully created MIDI file back to Android, where you can play it right in the app. The total process takes between 5-10 seconds.

### Challenges we ran into
On the mobile end, we wanted to make the application target Android 10. This meant carefully navigating various privacy demands that were both scarcely documented, and completely new to our team's developers. Meanwhile on the back end, it was tough performing feature detection and filtering out noise with OpenCV.

### Accomplishments that we're proud of
Despite the barriers we faced, our team is proud to have created an end-to-end application with so little time. We are also proud to have had such attention to detail, even going as far as to implement complicated animations just to open a dialog in Android.
