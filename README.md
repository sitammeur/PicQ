# PicQ

Visual Question Answering is answering open-ended questions based on an image. They output natural language responses to natural language questions about the content of an image. This project uses one of the popular multimodal models, [**MiniCPM-o 4.5**](https://huggingface.co/openbmb/MiniCPM-o-4_5) from the Hugging Face model hub.

[**MiniCPM-o 4.5**](https://huggingface.co/openbmb/MiniCPM-o-4_5) is the latest and most capable model in the MiniCPM-o series. The model is built in an end-to-end fashion based on **SigLip2**, **Whisper-medium**, **CosyVoice2**, and **Qwen3-8B** with a total of 9B parameters. It exhibits a significant performance improvement, and introduces new features for full-duplex multimodal live streaming.

## Project Structure

The project is structured as follows:

- `src\`: The folder containing the project's source code.

  - `minicpm\`: The folder containing the source code for the application's main functionality.

    - `model.py`: The file that contains the code for loading the model, tokenizer, and processor.
    - `response.py`: The file that contains the function for generating the response for the input image and question.

  - `config.py`: This file contains the configuration for the used model.
  - `logger.py`: This file contains the project's logging configuration.
  - `exception.py`: This file contains the exception handling for the project.

- `app.py`: The main file that contains the Gradio application for visual question answering.
- `requirements.txt`: The file containing the project's required dependencies.
- `LICENSE`: The license file for the project.
- `README.md`: The README file that contains information about the project.
- `assets`: The folder containing screenshots for working on the application.
- `images`: The folder that contains the images for testing the application.

## Tech Stack

- Python (for the programming language)
- PyTorch (for the deep learning framework)
- Hugging Face Transformers Library (for the visual question-answering model)
- Gradio (for the web application)
- Hugging Face Spaces (for hosting the gradio application)

## Usage

The web application allows you to input an image and a question. The model will then generate an answer based on the image and the question. It can assist visually impaired individuals by providing access to web and real-world images, improving image retrieval by retrieving specific characteristics, and enabling video search by retrieving specific snippets or timestamps based on search queries. The application can also be applied in educational settings to provide a more interactive learning experience.

## Results

For results, refer to the `assets/` directory for the output screenshots, which show the application in action.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please raise an issue to discuss the changes you want to make. Once the changes are approved, you can create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or suggestions regarding the project, feel free to reach out to me on my GitHub profile.

Happy coding! 🚀
