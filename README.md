# Hand Gesture Coffee Order (OPEN CV)

## Overview

The Hand Gesture Coffee Order project utilizes OpenCV and computer vision technology to provide a gesture-based coffee ordering system. This innovative approach replaces traditional menus with a contactless and intuitive gesture interface, making it easy to place coffee orders using hand gestures.

## Prerequisites

Before you begin, ensure you have the following installed on your PC:

- **Python 3.x**
- **OpenCV**: A library for real-time computer vision

## Installation

### Install Wheel

Wheel is a package manager for Python that simplifies the installation of packages:
```bash
pip install wheel


### Install Requirements

Install all the required packages listed in `requirements.txt`:
```bash
pip3 install -r requirements.txt
```

### Handling Mediapipe Issues on macOS with M1/M2

If you encounter issues with the `mediapipe` package (common on macOS with M1/M2), you may need to adjust the package configuration:
1. Open the `requirements.txt` file.
2. Uncomment the line specifying the `mediapipe` version for Silicon processors.
3. Comment out the existing `mediapipe` entry.

This change ensures compatibility with Apple Silicon processors.

## Usage

After installation, you can run the application to start the gesture-based coffee ordering system. Execute the main script with:
```bash
python main.py
```

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request. For detailed contribution guidelines, see the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- **OpenCV**: For its powerful computer vision capabilities.
- **mediapipe**: For hand gesture detection and tracking.

For further assistance, please open an issue or contact the project maintainers.
```
Enjoy your gesture-based coffee ordering experience!
