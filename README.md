# NYC Food Scrap Drop-Off Sites Chatbot

This project implements a custom OpenAI chatbot designed to provide information about food scrap drop-off sites in New York City. By leveraging the Retrieval-Augmented Generation (RAG) technique, the chatbot combines the strengths of both retrieval-based and generative models. This allows it not only to pull in accurate data from  the `nyc_food_scrap_drop_off_sites.csv` file, but also to generate contextually relevant responses. As users inquire about locations, operating hours, and guidelines for food scraps, the RAG approach ensures they receive precise and up-to-date information.

# Implementation

To set up the chatbot, clone this repository and follow the installation instructions below:

# Requirements

- Python 3.7+
- OpenAI API Key
- Dependencies:
  - `pandas`
  - `openai`
  - 'fuzzywuzzy'
  - 're'
# Conclusion

The implementation of the RAG technique in our NYC Food Scrap Drop-Off Sites Chatbot significantly enhances the user experience. By seamlessly integrating retrieval and generation capabilities, the chatbot effectively provides reliable information while maintaining a conversational tone. This combination not only improves the accuracy of responses but also creates a more engaging interaction for users seeking to learn about sustainable practices in waste management. Moving forward, the RAG framework could be further refined and expanded to cover additional types of inquiries, making it an invaluable resource in enhancing public awareness of food scrap recycling initiatives.
