# Video Notes Generator

This is a simple application to generate notes from a video or YouTube video URL. It transcribes the audio content of the video using the Google Web Speech API, corrects any spelling mistakes, reduces repeated words, and generates a document containing the notes.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/video-notes-generator.git
    ```

2. Navigate to the project directory:

    ```bash
    cd video-notes-generator
    ```

3. Install the required Python libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app:

    ```bash
    streamlit run notes_generator_app.py
    ```

2. Open the URL displayed in your terminal in a web browser.

3. Choose an option:
    - **Local Video File**: Upload a video file from your local machine.
    - **YouTube Video URL**: Enter the URL of a YouTube video.

4. Follow the prompts to generate notes from the video.


## Requirements
Python 3.x
Streamlit
moviepy
pytube
SpeechRecognition
docx
autocorrect

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/new-feature`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
