# Bulgarian TTS Dataset (Experimental)

This repository contains an experimental text-to-speech (TTS) dataset for the Bulgarian language, intended for use with [Piper](https://github.com/rhasspy/piper).

## Project Overview
This dataset is designed to provide high-quality speech samples for training Bulgarian TTS models. It follows the standard Piper dataset format.

## Dataset Structure
- `wav/`: Contains the audio files in WAV format (22,050 Hz, 16-bit, mono).
- `metadata.csv`: Contains the transcription for each audio file in the format `file_name|text`.

## Requirements
- Python 3.x
- [Piper Training](https://github.com/rhasspy/piper/tree/master/src/python) tools

## Usage
To use this dataset with Piper, follow the official training guide provided in the Piper repository.

## Disclaimer
This is an experimental repository. Data quality and completeness may vary.

## License
[Insert License Information Here]
