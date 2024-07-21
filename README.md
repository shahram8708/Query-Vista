# Query Vista 🤖

**Query Vista** is a web application that allows users to upload multiple images, ask a question, and get answers based on all uploaded images. It leverages Google's Gemini AI to provide insights and generate content in response to user prompts.

## Features

- **Drag & Drop Multiple Images**: Easily upload multiple images by dragging and dropping them or selecting from your file system.
- **Prompt Input**: Enter a question or prompt related to the images you’ve uploaded.
- **Generate Insights**: The application sends your images and prompt to the Gemini AI model to generate content.
- **Audio Playback**: Play or stop the generated response audio.
- **Text Copying**: Copy the response text to your clipboard.

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/shahram8708/query-vista.git
    cd query-vista
    ```

2. **Create a Virtual Environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set Up Environment Variables**

    Create a `.env` file in the root directory and add your API key:

    ```env
    API_KEY=your_google_generativeai_api_key
    ```

5. **Run the Application**

    ```bash
    python app.py
    ```

    The application will start and be accessible at `http://127.0.0.1:5000/`.

## Usage

1. **Upload Images**: Drag and drop multiple images or click to select them.
2. **Enter Prompt**: Type your question or prompt into the text input field.
3. **Submit**: Click the ✅ button to submit your images and prompt.
4. **View Results**: The results will be displayed below, and you can play or stop the audio response, and copy the text.

## Contributing

If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b`).
3. Commit your changes (`git commit -am`).
4. Push to the branch (`git push origin`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [Shah Ram](mailto:shahram8708@gmail.com).
