This Python script resizes images located in the same folder as the script itself without using separate input and output folders. 
It uses the os module to list all files in the current directory and the PIL.Image class from the Pillow library to resize them. 
The script checks each file’s extension to ensure it is an image, resizes it to a fixed size (300, 300) pixels, and saves the new image in the same location with _resized added to its filename. 
This approach preserves the original images while creating resized copies alongside them.
