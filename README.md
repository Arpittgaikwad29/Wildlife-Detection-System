# Wildlife Detection System

## Overview

The Wildlife Detection System is an AI-powered application designed to detect and alert authorities about the presence of wildlife, particularly tigers and other potentially dangerous animals, in real-time. Utilizing the YOLOv8 (You Only Look Once) model, this system enhances safety in monitored areas by providing timely alerts and automated monitoring capabilities.

## Features

- **Real-Time Animal Detection:** Uses YOLOv8 for efficient identification of wildlife in video feeds.
- **Alert Notifications:** Sends alerts upon detection, integrated with messaging services like WhatsApp.
- **User-Friendly Interface:** Built with Streamlit, featuring easy controls to start and stop detection, as well as view detected images.
- **Customizable Monitoring Areas:** Allows users to define specific detection zones on a map.
- **Seamless Video Processing:** Continuous monitoring without interruptions, optimized for minimal redundant alerts.

## Requirements

- Python 3.x
- TensorFlow
- PyTorch
- OpenCV
- Streamlit
- Additional libraries as specified in `requirements.txt`

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/YourUsername/Wildlife-Detection-System.git
   cd Wildlife-Detection-System
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the application:**

   ```bash
   streamlit run app.py
   ```

2. **Configure the detection settings:**
   - Set the area for wildlife monitoring using the interactive map.
   - Choose detection parameters and thresholds as needed.

3. **Start Detection:**
   - Click the **"Start"** button to begin monitoring.
   - Upon detection, the system will capture images and send alerts as configured.

4. **Stop Detection:**
   - Click the **"Stop"** button to end monitoring. Detected images will be displayed for review.

## Configuration

To configure the alert system (e.g., WhatsApp notifications), edit the relevant sections in the configuration file or within the main application script to include your API credentials and preferences.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **YOLOv8**: For real-time object detection capabilities.
- **Streamlit**: For creating an interactive user interface.
- **OpenCV**: For video processing functions.
- Special thanks to all contributors and supporters of wildlife conservation efforts.

---

Feel free to modify this README to fit your specific project details and preferences!
