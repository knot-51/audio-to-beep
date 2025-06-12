# audio-to-beep
Extract dominant frequencies from audio(preferably a vocal only) and generate beep sounds.
This is my final year project for Audio to Sheet Music Converter, it has not reached the sheet music part so it creates a beep instead.

## Features
- Frequency detection using FFT
- Converts each dominant frequency into a tone (beep)
- Silent where no strong frequency is detected
- Early prototyping of sheet music automation

## Tools Used
- Python
- NumPy
- SciPy
- Matplotlib (optional for plotting)

## How to Use
- Run the original audio through a vocal separator tools like OpenUnmix or BandLab.com
- Change the audio_file_input to desired directory and interval to desired value then run.
