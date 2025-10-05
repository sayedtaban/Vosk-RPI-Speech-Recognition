**Vosk-RPI-Speech-Recognition with SaraKIT**

**Vosk Speech Recognition Toolkit**
Vosk is an offline open-source speech recognition toolkit, facilitating speech recognition in over 20 languages and dialects including English, German, French, Spanish, and many more. Its models are compact (around 50 Mb) but support continuous large vocabulary transcription, offer zero-latency response with a streaming API, feature reconfigurable vocabulary, and identify speakers. Vosk caters to a range of applications from chatbots and smart home devices to virtual assistants and subtitle creation, scaling from small devices like Raspberry Pi or Android smartphones to large clusters.

**Installing on SaraKIT:**
Assuming the basic SaraKIT drivers are already installed ([https://sarakit.saraai.com/getting-started/software](https://sarakit.saraai.com/getting-started/software)), follow these steps to install:

```bash
sudo apt-get install pip
sudo apt-get install -y python3-pyaudio
sudo pip3 install vosk

git clone https://github.com/sayedtaban/Vosk-RPI-Speech-Recognition
cd Vosk-RPI-Speech-Recognition
```

Start speech recognition by running:

```bash
python SpeechRecognition.py
```

The effects of this simple yet powerful script can be seen in the video below:

https://github.com/sayedtaban/Vosk-RPI-Speech-Recognition/assets/35704910/5c7b53b0-90b7-4e00-9055-686648546965

