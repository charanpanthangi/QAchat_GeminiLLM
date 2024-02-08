
Imagine an image model that doesn't just see, but also understands and talks! That's what you get with an image model using Gemini LLM. Here's a simplified breakdown:

Gemini LLM: This is a powerful language model, similar to me, but trained on both text and images. It can understand the meaning of words and the content of pictures.

Image Model: This part analyzes the visual information in an image, recognizing objects, scenes, and their relationships.

Together: Think of them as a team. The image model "sees" the picture, then explains it to the LLM in "language" the LLM understands. The LLM then uses its vast knowledge and reasoning abilities to interpret and respond to your questions or requests about the image.

What can it do?

Answer questions about an image: "What animals are in this picture?"
Generate descriptions of an image: "Write a poem inspired by this landscape."
Compare and contrast images: "How are these two faces similar?"
Extract information from images: "What data is represented in this chart?"
Overall, an image model using Gemini LLM opens up exciting possibilities for understanding and interacting with visual information in new ways.


## Dependencies and Installation
----------------------------
To install the MultiPDF Chat App, please follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

3. Obtain an API key from Gemini  and add it to the `.env` file in the project directory.
```commandline
Gemini_API_KEY=your_secrit_api_key
```

## Usage
-----
To use the MultiPDF Chat App, follow these steps:

1. Ensure that you have installed the required dependencies and added the Gemini API key to the `.env` file.

2. Run the 
   ```
   streamlit run vision.py
   ```

3. The application will launch in your default web browser, displaying the user interface.

4. Load multiple PDF documents into the app by following the provided instructions.

5. Ask questions in natural language about the loaded PDFs using the chat interface.

