## Gemini Image Demo

This project uses the Gemini Generative Model to generate content based on an input prompt and an image. The model is accessed using the Google GenAI API.

# Setup
- To run this project, you will need to have Python installed on your machine. Additionally, you will need to have a Google Cloud account and set up the GenAI API with an API key.

- Install the required libraries by running 
```$ pip install -r requirements.txt```

- Create a ```.env file``` in the root directory and add your Google API key as follows: ```GOOGLE_API_KEY=your-api-key```

- Run the application with ```$ streamlit run app.py```

## Usage
- Enter a prompt in the text input box.
- Upload an image using the file uploader.
- Click the "Tell me about the image" button to generate a response.
The generated response will be displayed below the button. The model uses the input prompt and the uploaded image to generate the response.

## Contact
For any questions or issues, please open an issue on the project's GitHub repository.
