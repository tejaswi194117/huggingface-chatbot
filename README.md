
#  Hugging Face Based Chatbot (using flan-t5-large)

This project is a command-line style chatbot implemented in Google Colab using the `google/flan-t5-large` model from Hugging Face.

##  Features

- Can follow instructions
- Built using Google Colab
- Has a loop where the user can keep entering queries until they type `/exit`

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Run cells in this order:
   - Install Transformers
   - Load model (initially)
   - Define chat memory and logic
   - Initialize model & memory
   - Run the chat loop

##  Sample Interaction
-User: What is the capital of France?
-Bot: Paris

-User: What is the capital of Germany?
-Bot: Berlin

-User: /exit
- Exiting chatbot. Goodbye!

##  Files Included

- `chatbot_flan_t5.ipynb` - Main Colab notebook
- `README.md` - This file
- `requirements.txt` - List of dependencies

##  Demo Video



 [Click here to watch the demo video on Loom](https://www.loom.com/share/d0a1608153084d2eacc59134335f61b3?sid=fa6d2dd3-4e54-442f-9a06-142c031d8dc9)

