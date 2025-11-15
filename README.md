# AIHC-healthcare-chatbot

# AIHC - AI Healthcare Chatbot

A modern, interactive AI-powered healthcare chatbot application built with HTML, CSS, and JavaScript. AIHC provides users with quick health information, guidance, and wellness tips through a conversational interface.

## Features

- **User Authentication**
  - Secure login and registration system
  - Email-based user accounts
  - Password validation and confirmation

- **Interactive Chat Interface**
  - Real-time messaging with AI assistant
  - User-friendly chat box with message history
  - Automatic message scrolling
  - Responsive design for all devices

- **Healthcare Knowledge Base**
  - Comprehensive responses to common health concerns
  - Topics covered: headaches, fever, cold, cough, pain, stress, sleep, diet, exercise, diabetes, blood pressure, anxiety, depression, allergies, asthma, and more
  - Natural language processing for user queries
  - Contextual greetings and responses

- **Modern UI/UX**
  - Beautiful gradient design
  - Smooth animations and transitions
  - Mobile-responsive layout
  - Custom scrollbar styling
  - Professional styling with animations

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required - runs entirely in the browser

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/AIHC.git
cd AIHC
```

2. Open the application:
   - Simply open `index.html` in your web browser, or
   - Use a local server (recommended):
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (with http-server installed)
http-server
```

3. Navigate to `http://localhost:8000` in your browser

## Project Structure

```
AIHC/
├── index.html          # Main application file
├── login.html          # Login page (reference)
├── register.html       # Registration page (reference)
├── script.js           # JavaScript logic and chatbot functionality
├── style.css           # Styling and animations
├── .vscode/
│   └── launch.json     # VS Code debugging configuration
└── README.md           # This file
```

## Usage

### Registering a New Account

1. Click "Register here" on the login page
2. Enter your full name, email, and password
3. Confirm your password
4. Click "Register"
5. Login with your credentials

### Using the Chatbot

1. Login with your account credentials
2. Type your health-related questions in the chat input
3. Press Enter or click the Send button
4. Receive instant health information and guidance
5. Click "Logout" to end your session

### Example Queries

- "I have a headache"
- "How can I manage stress?"
- "Tell me about healthy diet"
- "I'm having trouble sleeping"
- "How much exercise should I do?"

## Technology Stack

- **HTML5** - Structure and semantic markup
- **CSS3** - Styling, gradients, animations, and responsive design
- **JavaScript (ES6)** - Core functionality, chat logic, and user management
- **LocalStorage** - Client-side data persistence (can be extended to backend)

## Key Features Explained

### Authentication System
- User data stored in JavaScript objects (in-memory)
- Can be easily extended to use a backend database
- Password validation with minimum 6 characters
- Email uniqueness verification

### Chatbot Intelligence
- Keyword-based response matching
- Context-aware messaging
- Natural conversation flow with greetings, thanks, and goodbyes
- Fallback responses for unknown queries
- Personalized responses using user's name

### Responsive Design
- Mobile-first approach
- Breakpoints for tablets and desktop
- Touch-friendly interface
- Optimized chat box for all screen sizes

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- [ ] Backend API integration for persistent data storage
- [ ] Advanced NLP using machine learning models
- [ ] Real doctor consultation booking
- [ ] Medical history tracking
- [ ] Appointment scheduling
- [ ] Multi-language support
- [ ] Dark mode theme
- [ ] Push notifications
- [ ] Integration with health APIs

## Limitations & Disclaimers

⚠️ **Important**: AIHC is an educational project and should not be used as a substitute for professional medical advice. Always consult with a licensed healthcare provider for:
- Accurate diagnosis
- Personalized treatment plans
- Emergency medical situations
- Prescription medications

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the MIT License - see the LICENSE file for details.

## Author

**Saksham** - Initial work

## Support

For questions, issues, or suggestions, please open an issue in the GitHub repository.

## Acknowledgments

- Inspired by modern healthcare chatbot applications
- Built with responsive design best practices
- UI/UX influenced by contemporary web applications

---

**Note**: This is a frontend-only application. To use in production, connect it to a secure backend API for user authentication and data persistence.


SCREENSHOT

registeration page - 

<img width="1309" height="856" alt="Screenshot (150)" src="https://github.com/user-attachments/assets/3c5936dc-9d4b-405b-b15f-474a88d270de" />


login page - 

<img width="1326" height="845" alt="Screenshot (152)" src="https://github.com/user-attachments/assets/68cc6087-9600-4dcf-9a92-310d41d95fb4" />

home page - 

<img width="1308" height="855" alt="Screenshot (153)" src="https://github.com/user-attachments/assets/7562a5a6-617b-4d53-829f-6d5853f863c7" />

<img width="1308" height="855" alt="Screenshot (153)" src="https://github.com/user-attachments/assets/b8a741b9-68ed-435b-aeea-61d7de7fb004" />                                                                                                                                                                                        

