# Arivagam.

This project is a Flask-based educational platform that integrates user authentication, YouTube video search with automatic transcript extraction, and a chat feature. It utilizes MongoDB for user data storage and integrates various APIs for functionality.

## Features

- **User Authentication**: Allows users to sign up and log in securely.
- **YouTube Video Search**: Enables users to search for videos and extracts transcripts automatically.
- **Chat Functionality**: Provides a chat interface for users to interact.
- **Data Storage**: Utilizes MongoDB for storing user data and interaction histories.

## Technologies Used

- **Backend**: Flask, MongoDB, pymongo
- **YouTube API**: youtubesearchpython, youtube_transcript_api
- **Frontend**: HTML, CSS, JavaScript
- **Authentication**: Flask session management and bcrypt for password hashing

## Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/prithiknataraj/Arivagam..git
   cd Arivagam.
   ```

2. **Install Dependencies**:

   ```bash
   pip install Flask pymongo youtubesearchpython youtube_transcript_api
   ```

3. **Configure MongoDB**:
   
   - Install MongoDB and start the MongoDB service.
   - Ensure MongoDB URI is correctly set in the Flask application (`app.py`).

4. **Run the Application**:

   ```bash
   python app.py
   ```

5. **Access the Application**:

   - Open a web browser and go to `http://localhost:5000` to explore the application.

## Usage

- **Sign Up**: Create a new account with a unique username and password.
- **Log In**: Authenticate with your username and password to access personalized features.
- **Video Search**: Enter a search query to find relevant YouTube videos, and the transcript will be automatically extracted.
- **Chat**: Engage in real-time chat discussions.

## Future Enhancements

- Implement more robust error handling and validation for user inputs.
- Enhance UI/UX design for better user interaction.
- Add more features such as video bookmarking and personalized recommendations.

## Contributors

- Nithish S
- Sasmitha B
- Sujay R
