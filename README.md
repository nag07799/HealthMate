# HealthMate 🩺

**HealthMate** is an AI-powered healthcare chatbot designed to provide personalized health advice. The chatbot recommends nearby doctors based on your location and suggests alternative treatments like Ayurveda and Homeopathy. The app aims to empower users to make informed health decisions quickly and efficiently.

## Features 🌟

- **Personalized Health Advice**: Get tailored recommendations based on your symptoms and health queries.
- **Alternative Medicine**: Receive suggestions for Ayurvedic, Homeopathic, and Allopathic treatments.
- **Doctor Locator**: Find the nearest doctors based on your location and preferred treatment method.
- **Interactive Chat Interface**: Engaging and user-friendly chat interface powered by state-of-the-art AI models.
- **Local Contact Information**: Provides contact details for doctors in the North Texas region.

## Technologies Used 🛠️

- **Streamlit**: For building the interactive web application.
- **PyTorch**: For handling AI models and embeddings.
- **FAISS**: For efficient similarity search and vector retrieval.
- **Azure OpenAI**: For generating AI-powered responses using GPT-based models.
- **Transformers**: Used for text embeddings via sentence-transformers.

## Installation 🖥️

To run HealthMate locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/healthmate.git
   cd healthmate
   ```

2. Install the required dependencies:
   ```bash
   pip install streamlit faiss-cpu openai pyngrok torch transformers
   ```

3. Run the application:
   ```bash
   streamlit run healthmate_app.py
   ```

## Usage 🚀

1. Launch the application by running the above command.
2. Interact with the chatbot by typing your symptoms or health-related queries.
3. The chatbot will provide personalized advice, suggest alternative treatments, and offer local doctor recommendations.
4. If you want to end the conversation, simply type "bye".

## Important Notes 📌

- This chatbot is intended to provide general health advice and should not be used as a substitute for professional medical consultation. Always consult with a qualified healthcare provider before making any medical decisions.
- Ensure you have an active internet connection to access the AI services and location-based features.

## Contributing 🤝

Contributions are welcome! If you'd like to improve HealthMate or fix any bugs, feel free to submit a pull request or open an issue.


## Acknowledgments 🙏

- **Streamlit** for making it easy to create web apps with Python.
- **Azure OpenAI** for providing the AI models used in generating responses.
- **FAISS** for efficient similarity search and vector management.
- **The Transformer library** by Hugging Face for the powerful text embeddings.

