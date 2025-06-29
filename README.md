# Audio-to-Beep
Extract dominant frequencies from audio(preferably a vocal only) and generate beep sounds.
This is an early prototype for my final-year project, originally intended as an **Audio to Sheet Music Converter**. Since sheet music rendering is not yet implemented, the current version outputs beeps instead of musical notation.

## Features
- Frequency detection using FFT
- Converts each dominant frequency into a tone (beep)
- Silent where no strong frequency is detected
- Early prototyping of sheet music automation

## Tools Used
- Python
- NumPy
- SciPy
- Matplotlib (for plotting)

## How to Use
- Run the original audio through a vocal separator tools like OpenUnmix or BandLab.com
- Open the Python file and set:
   - `audio_file_input` to the path of your processed vocal-only file  
   - `interval` to your desired sampling interval (in seconds)
- Run the code and get the output file frome the code's directory
