# Image and Live Video Encryption System

## Overview
This project presents an innovative **Image and Live Video Encryption System** that utilizes the **Lorenz Chaos System** as its foundational algorithm. The system is designed for secure image and video transmission, employing advanced techniques in image processing and encryption. The implementation is carried out on the **MyRIO** embedded hardware platform, enabling real-time processing of images and live video feeds.

## Technologies Used
- **LabVIEW**: The primary development environment used to implement the system.
- **MyRIO**: An embedded hardware platform that provides the necessary computational power and I/O capabilities for real-time image and video processing.
- **Lorenz Chaos System**: A chaotic system that provides high security through its sensitivity to initial conditions, making it difficult to predict the output without the correct keys.
- **S-Box (Substitution Box)**: Used to provide confusion in the encryption process by replacing bits of the input data with bits from a predefined table.
- **Image Processing Techniques**: Various techniques to manipulate and analyze the image data before and after encryption, ensuring efficient processing and improved security.

## Prerequisites
To run this project, you will need to install **LabVIEW** and have access to a **MyRIO** module.

### System Requirements
- LabVIEW (version X.X or later)
- MyRIO hardware module
- Compatible operating system (Windows recommended)
- Required libraries and toolkits (if any) as specified in the LabVIEW installation

## Installation Steps
1. **Install LabVIEW**:
   - Download and install LabVIEW from the official website. Follow the installation instructions provided.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Image-Video-Encryption-System.git
   cd Image-Video-Encryption-System


3. **Open the Project**:
   - Launch LabVIEW.
   - Open the project file (`.lvproj`) located in the cloned directory.

4. **Configure MyRIO**:
   - Ensure your MyRIO module is connected to your computer.
   - Configure the MyRIO settings in LabVIEW to recognize and communicate with the hardware.

5. **Run the VI**:
   - Open the main VI (Virtual Instrument) and run it to start the encryption process.
   - Follow the prompts to select an image or live video feed for encryption.

## Usage
- Select the desired input source (image or video).
- Adjust the parameters for the Lorenz Chaos System and S-Box as needed for your encryption requirements.
- Start the encryption process and observe the encrypted output.

## Features
- **Real-Time Video Encryption**: Supports live video encryption for enhanced security.
- **Robust Image Encryption**: Provides secure encryption of static images.
- **Customizable Parameters**: Users can modify encryption parameters for different levels of security.
- **Embedded System Integration**: Implemented on the MyRIO platform for real-time processing capabilities.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- **National Instruments** for providing LabVIEW and MyRIO.
- The concept of chaotic systems, particularly the Lorenz system, for inspiring the encryption algorithm.

## Contact
For questions or inquiries about this project, please contact me at [your.email@example.com].
