# Scoobot with Facial Recognition

This project demonstrates a security robot that uses an ESP32-CAM for facial recognition and integrates with social media platforms like Facebook, LinkedIn, and Twitter (X). The system captures facial images, performs face detection, and then uploads the image to the cloud for further analysis and comparison with public profiles.

## Project Structure

- `esp32-cam/` - Contains the Arduino code for capturing images and performing face detection using the ESP32-CAM.
- `nodeMCU/` - Contains the Arduino code for NodeMCU to communicate with the cloud and social media APIs.
- `cloud/` - Contains Python scripts for API integration and face recognition (for cloud-based processing).

## Installation

### Hardware Requirements

- ESP32-CAM
- NodeMCU (ESP8266)
- Motors/Sensors (if needed for robotic movement)

### Software Requirements

- Arduino IDE (with ESP32/ESP8266 support)
- Python 3.x (for cloud integration)
- Social Media API tokens

### Setup

1. Clone this repository to your local machine.
2. Set up the ESP32-CAM and NodeMCU hardware as described in the code files.
3. Install necessary libraries in Arduino IDE for ESP32 and ESP8266.
4. Replace placeholders in the code with your Wi-Fi credentials and API tokens.
5. Upload the code to the respective boards.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
