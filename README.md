# Chat with Websites

This project allows users to interact with websites using a conversational AI powered by Streamlit and various language processing tools. The application leverages Streamlit for the user interface and integrates several libraries from the LangChain ecosystem for natural language processing tasks.

## Features

- **Website Interaction:** Users can chat with a website using natural language.
- **Context-aware Responses:** The AI maintains context across interactions to provide relevant responses.
- **Dynamic Embeddings:** Uses Google Generative AI Embeddings for semantic understanding.
- **Conversation History:** Maintains a history of the conversation for context preservation.

## Libraries Used

- **Streamlit:** Frontend UI framework for Python.
- **LangChain Core:** Provides message handling and chaining capabilities.
- **LangChain Community:** Includes document loaders and vector stores.
- **LangChain Google GenAI:** Integration for Google's Generative AI capabilities.
- **dotenv:** Loads environment variables, crucial for API keys.

## Installation

1. Clone the repository:
    
    ```
    git clone <https://github.com/your-username/your-repository.git>
    cd your-repository
    
    ```
    
2. Install dependencies:
    
    ```
    pip install -r requirements.txt
    
    ```
    
3. Set up environment variables:
    
    Create a `.env` file in the root directory and add your Google API key:
    
    ```
    GOOGLE_API_KEY=your_google_api_key_here
    
    ```
    

## Usage

1. Run the Streamlit app:
    
    ```
    streamlit run app.py
    
    ```
    
2. Enter a website URL in the sidebar and start chatting!

## Example

![demo.gif](demo.gif)

## License

This project is licensed under the MIT License - see the [LICENSE](https://www.notion.so/LICENSE) file for details.

## Acknowledgments

- **Streamlit Team** for providing an excellent platform for building interactive applications.
- **LangChain Contributors** for developing open-source tools for natural language processing.
