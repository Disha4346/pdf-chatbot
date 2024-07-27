# PDF Chatbot with Gemini Pro and Streamlit

## Objective

Develop a chatbot that can interact with multiple PDF documents in a natural and coherent manner using a large language model (LLM) such as Gemini Pro. The chatbot should be capable of understanding and responding to various user queries, generating summaries, and providing responses to questions raised by the user.

## Features

- Upload and interact with multiple PDF documents.
- Generate summaries and respond to user queries based on the content of the PDFs.
- Simple and intuitive user interface built with Streamlit.
- Utilizes the Gemini Pro API for powerful language model capabilities.

## Demo Video

Watch the [demo video](https://github.com/Disha4346/pdf-chatbot/blob/main/video-demo/pdf%20analyzer.mp4) to see the chatbot in action.

## Installation

Follow these steps to set up and run the chatbot:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Disha4346/pdf-chatbot.git
    cd pdf-chatbot
    ```

2. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up the Gemini Pro API key:**
   - Create a `.env` file in the project root directory.
   - Add your Gemini Pro API key to the `.env` file:
     ```
     GEMINI_PRO_API_KEY=your_api_key_here
     ```

4. **Run the application:**
    ```bash
    streamlit run app.py
    ```

## Usage

1. **Open the browser** and navigate to the URL displayed in the terminal after running the above command.
2. **Upload PDF documents** by clicking on the upload button.
3. **Interact with the chatbot** by typing your queries in the input box and receiving responses in real-time. The chatbot can summarize the uploaded PDFs and answer questions based on their content.

## Project Structure

```
pdf-chatbot/
├── app.py                  # Main application file
├── requirements.txt        # List of dependencies
├── .env                    # Environment variables file
├── README.md               # Project documentation
```

## Evaluation Criteria

- The chatbot should be able to understand and respond to user queries accurately and coherently.
- The chatbot should be able to generate summaries of the uploaded PDF documents.
- The code should be well-structured, readable, and follow best practices.
- The frontend interface should be user-friendly and visually appealing.
- The documentation should be clear, comprehensive, and easy to follow.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- [Gemini Pro API](https://example.com)
- [Streamlit](https://streamlit.io)
- [PyPDF2](https://pythonhosted.org/PyPDF2/)

