# Anger-recognition

## Description
This project is a real-time anger recognition system using WebSockets and deep learning models. It captures audio from a remote microphone, processes it, and predicts emotions using a pre-trained model.

## How It Works
- The sender script captures audio using `pyaudio` and streams it over WebSocket.
- The server receives the audio, processes it, and predicts emotions using a deep learning model.
- The receiver script processes the predicted emotions and displays them in a web interface.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/anger-recognition.git
   cd anger-recognition
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the server:
   ```sh
   python server.py
   ```
4. Start the sender:
   ```sh
   python sender.py
   ```
5. Open the web interface:
   - Open `index.html` in a browser.

## Files
- `sender.py`: Captures and streams audio.
- `server.py`: Handles WebSocket connections and processes audio data.
- `receiver.py`: Predicts emotions using a deep learning model.
- `static/`: Contains HTML, CSS, and JavaScript files for the web interface.

## Dependencies
- `pyaudio`
- `websocket-client`
- `aiohttp`
- `torch`
- `transformers`
- `numpy`
- `flask`

## Author
Developed by [Your Name].

## License
This project is licensed under the MIT License.

