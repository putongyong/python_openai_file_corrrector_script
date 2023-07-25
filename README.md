# python_openai_file_corrrector_script

# ChatGPT with OpenAI

Here's a Python script that uses the OpenAI API to power a simple chatbot that can correct the language of a docx file sentence by sentence. It uses the `text-davinci-003` engine for generating responses.

## Prerequisites

Before running the script, you need to set up an OpenAI API key. Follow these steps to get your API key:

1. Go to the OpenAI website: https://platform.openai.com/signup
2. Sign up for an account and log in.
3. Retrieve your API key from the dashboard.

## Installation

To run the script, you need to have Python installed on your system. Additionally, install the required libraries by executing the following command in your terminal or command prompt:

```python
pip install openai
```

```python
pip install python-docx
```

## Usage

1. Clone the repository to your local machine using the following command:

```
git clone https://github.com/putongyong/python_openai_file_corrrector_script/
```

2. Open the terminal or command prompt and navigate to the directory containing the Python script.

3. Run the script using the following command:

```python
python pythongptscript.py
```

4. The script will prompt you to enter your OpenAI API key. Provide the key as requested.

5. When the OpenAI API key is provided and valid, type "read file path/to/your/file.docx" in order to read the file and print it line by line in your terminal.

6. To correct a `.docx` file, type "correct file path/to/your/file.docx". It will start to correct the file sentence by sentence and print the corrected sentence in your terminal.

7. You can use the provided test file to test these two functions.
  
9. Otherwise, start a conversation with the chatbot. Simply type your message, and the chatbot will respond accordingly.

10. To exit the chat, type `exit`.

## Additional Notes

- The `max_tokens` and `temperature` parameters in the `chat_gpt` function can be adjusted to influence the response length and randomness.

- The corrected `.docx` file will be saved in the same directory as the original file with `_corrected` appended to the filename.

- Remember not to share your API key publicly or hardcode it in the script.

## Contributing

If you want to contribute to this project or have any suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
