# Tiled image Scrambler/Unscrambler

![](./readme_images/resolve_image.png)

Little application made with tkinter used to split and switch the tiles of an image.

Switch two tiles with left click, and rotate the tile with right click.

You can also use WASD (ZQSD on AZERTY) to move the entire image, with QE (AE on AZERTY) to rotate the entire image.

This project was originally made after being taunt by the meme used in FCSC 2024 with the challenge "Puzzle Trouble hard":

![](./readme_images/puzzle-trouble-meme.jpg)

The app might have a few bugs, this is my first project using tkinter. To start the app, install the requirements (`pip install -r requirements.txt`) and then launch the file `main.py`.

There's one known bug I couldn't solve when rotating the tiles:

If you're trying to rotate a squared tile, it happens that when the image is rezised by the app, the tiles are not squared anymore (usually by 1 pixel), so you're forced to make 180 degrees rotation instead of 90. If it happens, you can try to resize your window to update the image's size.