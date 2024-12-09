# BuddyBot

BuddyBot is a fully functional chatbot application designed to provide quick interactions with users. It allows text-based conversations, file uploads, and emoji support. Built using HTML, CSS, JavaScript, and integrates with a generative language model API to simulate intelligent bot responses.

## Features
- **Chat Interface**: A clean and simple chat interface for seamless user interactions.
- **Bot Responses**: Uses an AI model to generate responses based on the conversation history.
- **File Uploads**: Users can upload images which are displayed as part of the conversation.
- **Emoji Picker**: A built-in emoji picker allows users to add emojis to their messages.
- **Close/Toggle**: Options to close the chatbot or toggle its visibility.
- **Responsive Design**: Optimized for desktop and mobile use.

## Technologies Used
- **HTML5**: Structure of the chatbot interface.
- **CSS3**: Styling of the chatbot interface, including responsive design.
- **JavaScript**: Dynamic behavior for sending messages, handling file uploads, and interacting with the backend API.
- **Emoji Mart**: A library for integrating an emoji picker.
- **Generative Language API**: Used to generate bot responses (Google Gemini API).

## Setup Instructions

### Prerequisites
Make sure you have the following installed:
- A modern web browser (Chrome, Firefox, etc.)
- Text editor (e.g., VS Code, Sublime Text)

### Steps to Run Locally
1. Clone the repository:

   git clone https://github.com/yourusername/buddybot.git
 
2. Navigate to the project directory:
  
   cd buddybot
  
3. Open `index.html` in your preferred browser.

### Customizing API
To use your own API for generating responses, replace the `API_KEY` in `script.js` with your own key from Google or any other API provider you choose.


const API_KEY = "YOUR_API_KEY";
const API_URL = `https://generativelanguage.googleapis.com/v1/models/gemini-1.5-pro:generateContent?key=${API_KEY}`;


## Features in Detail

### Message Sending
- Users can type a message in the input area and press "Enter" (or click the send button) to send it.
- The chatbot responds after a delay, simulating a "thinking" indicator.
  
### File Upload
- Users can upload images by clicking on the attachment icon.
- The uploaded image will be displayed within the chat window.

### Emoji Picker
- Clicking the emoji button opens an emoji picker.
- Selected emojis are inserted into the message input field.

## License

This project is open source and available under the [MIT License](LICENSE).
