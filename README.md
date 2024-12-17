ECE 558 Project3 (Final Project) Option 1
=========================================
Unity ID: ygao46
Name: Yazhuo Gao
=========================================

## Quick Start
    Run the jupyter notebook by sequence
    Make sure the required libraries are installed

## GUI Interface
* 
    # Canvas
    Target Image | Source Image | Output Image

    # Load/Save
    Load Target Image: A browse window will appear for user to select image (.jpg format) manually as the target/background image.
    Load Source Image: A browse window will appear for user to select image (.jpg format) manually as the source/foreground image.
    Save Outputs: Save the (source image + black background), and (output image).
                  Please make sure the images are loaded.
    Save Clipped Image: Save the (source image clipped by mask + black background), (mask).
                        Please make sure the images are loaded.
    Clear Image: Clear all loaded and processed images
    Apply Pyramid Blending: Implement Gaussian and Laplacian pyramid to blend images.
                            Please make sure the images are loaded.
    
    # Resize Target Image
    A slidable bar to resize the source image from 1% to 200%.
    Reset Size: Reset size to default 100%.

    # Resize Source Image
    A slidable bar to resize the target image from 1% to 200%.
    Reset Size: Reset size to default 100%.

    # Drag&Draw Mode Switch
    Drag Mode: Switch to drag mode.
    Draw Mode: Switch to draw mode.

    # Select Mask
    Rectangle Mask: Draw a rectangle mask on the source image (a new drawing will clear the previous mask).
    Ellipse Mask: Draw a ellipse mask on the source image (a new drawing will clear the previous mask).
    Freeform Mask: Draw freeform mask (circle) on the source image with cursor movement (new drawings will not clear the previous mask).
    Eraser: Remove mask in freeform (circle) on the source image with cursor movement.
    Clear Mask: Clear all masks.
    * Note: Can remove the self.clear_mask() in mouse_action() to allow continuous drawing.

    # Log Message
    Report log and status message with user actions.

