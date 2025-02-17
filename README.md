# Face Recognition-Based Attendance System

## Overview
The Face Recognition-Based Attendance System is an automated system that marks attendance using facial recognition technology. This project eliminates the need for manual attendance tracking, reducing errors and ensuring accuracy.

## Features
- Real-time face detection and recognition
- Automatic attendance marking
- User-friendly interface
- Secure and reliable database storage
- Support for multiple users

## Technologies Used
- **Python** (OpenCV, NumPy, dlib, face_recognition)
- **Django/Flask** (for web interface, if applicable)
- **MySQL/SQLite** (for storing attendance records)
- **HTML, CSS, JavaScript** (for front-end, if applicable)

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- OpenCV
- dlib
- face_recognition library
- Flask/Django (if using a web-based system)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/face-recognition-attendance.git
   cd face-recognition-attendance
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## Usage
1. **Register Faces**: Add images of users for recognition.
2. **Start Attendance System**: Run the application to detect faces.
3. **Mark Attendance**: The system logs attendance in the database.
4. **View Attendance Records**: Check stored attendance logs.

## Folder Structure
```
face-recognition-attendance/
│── dataset/            # Stores registered face images
│── models/             # Pre-trained models for face recognition
│── database/           # Stores attendance records
│── app.py              # Main application file
│── requirements.txt    # Dependencies
│── README.md           # Project documentation
```

## Contributing
Contributions are welcome! Feel free to fork the repository, make modifications, and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any issues or feature requests, please open an issue on [GitHub](https://github.com/darshan27/face-recognition-attendance).

