# VoiceToText
The "Voice to Text" project is a web application that converts spoken words into text. The transcribed text is displayed on the web page and saved in a MySQL database.

![voiceToText](https://github.com/DeemaEssam/DeemaEssam.github.io/assets/106381596/c0017984-952f-4a80-8a35-4e17c77b59a8)

### Steps

1. create a MySQL database named `robot` that we used in the previous task with a table named `transcripts`.
2. Create an HTML file (`voiceToText.html`) with JavaScript for speech recognition and AJAX.
3. Create a PHP file (`voiceToText.php`) to handle database interactions.

### Code Explanation

#### HTML and JavaScript (`voice_to_text.html`)

- **HTML:** Structures the web page with a button to start voice input and a div to display the transcribed text.
- **CSS:** Styles the page with a light pink background, styled buttons, and a message box.
- **JavaScript:** Uses the Web Speech API to convert speech to text. Sends the transcribed text to the server using an AJAX request.

#### PHP (`save_transcript.php`)

- **PHP:** Handles the server-side processing. Inserts the transcribed text into the `transcripts` table in the `robot` database.
