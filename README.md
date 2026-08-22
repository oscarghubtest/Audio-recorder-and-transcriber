# 🎤 Audio Recorder and Transcriber

![Audio Recorder](https://img.shields.io/badge/Audio%20Recorder-and%20Transcriber-brightgreen)

Welcome to the **Audio Recorder and Transcriber** repository! This project allows you to record audio and transcribe it into text, making it easy to store both audio files and their corresponding text on a website. 

You can find the latest releases [here](https://github.com/oscarghubtest/Audio-recorder-and-transcriber/releases). Download the necessary files and execute them to get started.

## 📚 Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Support](#support)

## ✨ Features

- **Audio Recording**: Capture high-quality audio using your microphone.
- **Transcription**: Convert recorded audio into text using powerful APIs.
- **Storage**: Save audio files and their transcriptions in a structured database.
- **Web Integration**: Easily display audio and text on your website.
- **Cross-Platform**: Works on various operating systems with Python support.

## 🛠️ Technologies Used

This project leverages several technologies to provide a seamless experience:

- **Python**: The primary programming language used for development.
- **Google Cloud Speech-to-Text**: For accurate audio transcription.
- **Microsoft Azure**: An alternative service for transcription.
- **PyInstaller**: To package the application into a standalone executable.
- **Database**: For storing audio files and transcriptions.
- **Web Technologies**: HTML, CSS, and JavaScript for the front-end.

## 📥 Installation

To set up the Audio Recorder and Transcriber on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/oscarghubtest/Audio-recorder-and-transcriber.git
   cd Audio-recorder-and-transcriber
   ```

2. **Install Dependencies**:
   Ensure you have Python 3 installed. Then, install the required packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up API Keys**:
   You will need to create accounts on Google Cloud and Microsoft Azure to obtain API keys for transcription services. Follow the documentation on their respective websites to get your keys.

4. **Configure the Application**:
   Update the configuration file with your API keys and database settings.

5. **Run the Application**:
   Execute the main script to start the application:
   ```bash
   python main.py
   ```

## 📊 Usage

Once the application is running, you can use the following features:

1. **Record Audio**:
   Click the "Record" button to start capturing audio. Click "Stop" to finish the recording.

2. **Transcribe Audio**:
   After recording, select the audio file and click the "Transcribe" button. The application will process the audio and display the text.

3. **Store Data**:
   Save the audio file and its transcription to the database. You can view stored files and transcriptions on the website.

4. **Web Display**:
   Access the web interface to see your recordings and transcriptions neatly organized.

## 🤝 Contributing

We welcome contributions to improve the Audio Recorder and Transcriber. If you have suggestions or want to report issues, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch.
4. Submit a pull request with a clear description of your changes.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 📞 Support

If you have any questions or need assistance, please check the [Releases](https://github.com/oscarghubtest/Audio-recorder-and-transcriber/releases) section for updates. You can also open an issue in the repository for support.

---

Thank you for checking out the Audio Recorder and Transcriber project! We hope it serves your needs well.