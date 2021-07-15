# Image-Based-Music-Generation

This project uses a technique that analyses image properties and its pixel sequence
values and correlates it to properties of music determining the scale, pitch, progression and pace of
the music. All generated music is sonically cohesive, entirely generated from the image pixel data,
has no random elements or noise, and the results remain consistent throughout. Possible
applications of this study include getting new ideas for music composers and generating
accompanying music in various contexts.

# Proposed Work 

Our project is based on converting image to music using colour.
Music composition can be a very large topic that includes all aspects of music, like melody,
chord structure, rhythm, timbre, sound effect, performance indicator, etc. In the scope of this
paper, music composition is restricted to only pitch, duration and chord (in this context chord is
in its general meaning: notes that sound simultaneously). In other words, our task is to convert
an image into one or more series of notes of certain pitch and duration. We use image RGB
components where other than the overall image properties such as brightness contrast, the red
component in the pixel sequence affect the chord selection which affects the overall musical
property, green component affects the mood using a major or minor scale used for a part of the
bar and blue component affects the pace by defining the time signature of part of a bar to be
whole, half or quarter notes. This helps generate a layout to fill the musical piece with notes
depending on image sequence data links all characteristics of image onto the musical piece that
we generate using the said algorithm this helps remove any noise that may be required to
generate music, we add midi notes based off of the characteristics entirely, not involving any
randomness which renders unique midi sequence for each image. And gives consistent results
on the same image every time.

# Screenshots

![Screenshot 2021-07-15 at 12 33 38 PM](https://user-images.githubusercontent.com/79261660/125744038-9405f5f2-a0f4-4fa2-b749-220e004594e0.png)

![Screenshot 2021-07-15 at 12 33 54 PM](https://user-images.githubusercontent.com/79261660/125744071-2f62ec75-f190-4592-bbbe-154593c5059e.png)

# Deployed Project

https://iwpb2.herokuapp.com/
