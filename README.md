# canvaImage

This project is a simple image editor built with React and Fabric.js. It allows users to upload an image into a canvas area with a fixed frame (called a stencil). The image is scaled to match the canvas width, and users can zoom in, zoom out, or reset the image.

Features
Responsive Canvas: The canvas resizes automatically based on your screen size.

Single Image Display: Only one image is shown at a time. Uploading a new image removes the previous one.

Fit Image to Canvas Width: When an image is uploaded, it is scaled so that its width exactly fits the canvas.

Zoom In/Out: Users can zoom into or out of the image using buttons.

Reset Button: Resets the image to its original scale and position.

Redux Integration: Image scale and position are stored in Redux for state management.

How it Works
Canvas Setup: A Fabric.js canvas is created and resized to fit the screen.

Stencil Frame: A rectangle is added to the canvas as a frame. The image is clipped inside this frame.

Image Upload:

The image is scaled to match the canvas width.

It's centered inside the stencil.

If another image was already present, it is removed.

Zoom & Reset:

Zoom buttons increase or decrease the image size.

The reset button returns the image to its initial scale and position.

How to Use
Upload an image using the file input.

Use the Zoom In, Zoom Out, or Reset buttons to interact with the image.

Upload a new image to replace the old one.
