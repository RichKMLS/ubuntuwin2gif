# ubuntuwin2gif

This script allows you to easily create high-quality GIFs of windows on Ubuntu. The resulting GIFs are suitable for use in a GitHub README or other documentation.

<p align="center">
  <img src="https://github.com/RichKMLS/recordwin/assets/105183376/f02c5a5e-b811-4d9e-9a9f-c2884232a0b1"/>
  <br>
</p>

## Why use this script?
Making high-quality GIFs of a GNOME window can be a tedious and surprisingly complicated task. This script makes the task easier by automating the steps involved in recording the window, generating a color palette, and creating the final GIF. 

The script uses ffmpeg to record the screen and overlay it as a curved rectangle over a transparent background (which is used to account for the curved top corners of a GNOME window). It then generates a color palette from the recorded video to optimize the quality of the resulting GIF. Finally, it uses the generated color palette to create a high-quality GIF from the recorded video which opens automatically once created.

## How to use this script
To use this script, follow these steps:

Make sure you have ffmpeg and xwininfo installed on your system. If you don’t have them installed, you can install them using the following command:
```bash
sudo apt-get install ffmpeg x11-utils
```
Save the script.

Make the script executable by running the following command:
```bash
chmod +x ubuntuwin2gif
```
Run the script by executing it from the command line:
```bash
./ubuntuwin2gif
```
Click the window you want to record and the script will start. 

Use ctrl+c on your terminal to end recording.

Once the script completes, it will generate a high-quality GIF of the selected window and save it to your system and open it automatically.

Open an issue if you are having any problems or suggestions. Depending on what application you are trying to record you may need to adjust some variables.

Also, feel free to modify this script to function however you want. 
