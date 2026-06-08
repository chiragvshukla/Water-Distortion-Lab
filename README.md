# Water Distortion Lab

I came across a very cool photographer called [Oliver Palm](https://www.oliverpalmphoto.com/) who makes distorted photos using water, an iPad, and their camera. That got me thinking whether there was a way to simulate the water distortions rather than have to deal with the real thing. The usual way to do this would be to use Blender's simulations, OpenGL, or TouchDesigner. That said, I personally thought that this might be overkill and requires a decent bit of knowledge of the respective programs. Here's my attempt at a very simplified version of warping the images that's more noob user-friendly. It's nowhere near the quality of Oliver Palm's photos (and I wouldn't dare to take that from them), but hey, there's still some very cool effects you can get out of it. 

## Usage
This is a self-hosted webapp made in HTML using WebGL to take input images and render water-like effects (ripples, refraction, chromatic aberration, etc.) over them. 
Images can then be exported either as a short video or as a PNG.

To run it, just download the HTML file and open it in any modern browser.

Also available here if you don't want to download the html file: [water-distortion-lab.neocities.org](https://water-distortion-lab.neocities.org/)

Rendering happens completely locally, so don't worry about your images being collected. 

Please keep in mind that higher resolution images will require more time to process and also lead to bigger files overall, especially for video.

## Roadmap
This is very much meant to be a one-time project, so I won't be actively maintaining this repository. That said, I have some cool ideas for the future in a similar direction, so maybe I will release new versions and added features down the line if I have the time. 