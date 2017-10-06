# Alexa (Linux Voice Assistant)

## Install Speech Recognition module (this uses google speech api)

```
git clone https://github.com/Uberi/speech_recognition.git
cd speech_recognition
sudo apt-get install python-pyaudio python3-pyaudio
sudo python setup.py install
cd examples
python audio_transcribe.py```

## Start using the Voice Assistant

It will run in the background, when you call alexa you will see a box on right top saying recording..

