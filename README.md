# Resubmisson_Coding_One
The resubmit of Element 1 in Coding One

Zewen Xue 
21009879

Mimic link: https://mimicproject.com/code/0d0f3fb9-1c02-a33b-4925-76de4390087d

#Project Description：

Jazz Universe is an immersive piece that allows the viewer to adjust the perspective through the interaction of the mouse with the interface. Once activated, the glorious electronic patches of light move in rhythm with pleasant jazz music, creating an enchanting and immersive atmosphere. At first glance, this piece exudes unparalleled beauty.

However, as you start to move your mouse and gradually change your viewing angle, you will discover the truth about this world. This colorful, unreal world is actually made up of sharp geometries with a distinctive shape and a razor-sharp aesthetic. This highlights how beautiful qualities can change from one perspective to another. Perhaps it is through a broader, more holistic view that we can appreciate the diversity and complexity of things, and the imperfections behind the beauty.

Jazz Universe allows the viewer to experience the music while interactively thinking about the relationship between reality and illusion through the movement of a mouse. It conveys the important message that beauty is not static, but takes on many different faces as the perspective changes. Jazz Universe thus both expresses the appeal of the good side of things and, by expanding its horizons, suggests the need to maintain an interrogative diversity and an open mind to understand and appreciate the complexity of the world in a more holistic way.

In the code, the content of the page is placed in a div element which contains the title and subtitle of the piece. I unified the visual style by defining some CSS styles, including the page background color and hiding the scroll bar. For the JavaScript code section I defined some global variables and functions to initialise elements such as the scene, camera and light spot, and to implement animation rendering and user interaction. The init() function is used to initialise the scene, including the creation of the camera, light source and geometry; the animate() function implements the animation effect, allowing the light spot to move rhythmically; the onWindowResize() function is used to update the position and size of elements when the window size changes; the render() function is used to render the scene and update the state of elements; and the whole project also includes code to handle audio playback, as well as a fragment shader and vertex shader code for rendering the appearance of light spots. With Jazz Universe, the viewer can see the objective and subjective perspective of this universe change through mouse interaction. The bouncing light spots and the rhythm of the music form an organic resonance, while moving the mouse reveals the true construction of this colorful world.

Jazz Universe is optimised from my previous alternative project Rainbow Dreamland. During the improvement process I encountered some challenges and learnt valuable lessons from them. For example, I spent a lot of time working on the rhythm of the light spot and its alignment distribution so that it could be distributed over a large enough range. In addition, I experimented with different parameters and algorithms to get better results when it came to optimising the noise and rhythm of the audio, but in the end it wasn't ideal, so I abandoned the approach used in Rainbow Dreamland and opted to play a jazzy piece of audio directly to better fit the effect and atmosphere the piece was trying to convey.
