# VidEdtoo
Cool tool to convert MP4 to MP3 to not waste your time with sucks websites.

- **Select an MP4 video file**
- **Convert the video to MP3 audio**
- **Play the video with audio**
- **Play just the audio**
- **Stop playback**

### Main Features Explained

- **GUI**: Built with Tkinter, including buttons for each function and a display area for the video.
- **MP4 to MP3 Conversion**: Uses `moviepy` to extract audio from the selected video and save it as an MP3 file.
- **Video Playback**: Uses OpenCV (`cv2`) for video frames and `pygame` for audio. Video is displayed inside the window, and audio is played simultaneously.
- **Audio Playback**: Allows playing the extracted MP3 audio alone.
- **Threading**: Video playback runs in a separate thread so the GUI stays responsive.

### Requirements

You need to install these libraries if you haven't already:
```bash
pip install opencv-python moviepy pygame pillow
```

### How it Works (Step-by-Step)

1. **Select MP4**: Opens a file dialog to pick a video file.
2. **Convert to MP3**: Extracts audio and saves as MP3.
3. **Play Video**: Plays the video in the Tkinter window and the audio via pygame.
4. **Play Audio**: Plays only the MP3 audio.
5. **Stop**: Stops any playing audio and clears the video frame.

### Fun Notes

- The quirky comments at the end (`# I love burned botatoes!`, `# Meow!!!`) are just for fun and have no effect on the code.

---

If you want help with a specific part (adding features, fixing bugs, etc.), let me know!
