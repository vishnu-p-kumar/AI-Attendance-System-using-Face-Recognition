# AI-Based Attendance System Using Face Recognition

An intelligent attendance management system that leverages facial recognition technology to automate the attendance process for educational institutions.

## Features

- Real-time face detection and recognition
- Automated attendance marking
- Web interface for monitoring and management
- Secure storage of attendance records
- Integration with timetable system
- Date of birth verification for student authentication

## Project Structure

```
├── app.py                 # Main Flask application
├── background_image/     # Background images for UI
├── excel_tracker.py      # Excel file handling
├── face_recognition_run.py  # Face recognition implementation
├── images/              # Student face images database
├── simple_facerec.py    # Face recognition utilities
├── static/              # Static web assets
├── templates/           # HTML templates
├── timetable/           # Timetable management
├── CSE-A attendance.csv # Attendance records for CSE-A
├── CSE-C attendance.csv # Attendance records for CSE-C
└── student_dobs.csv     # Student date of birth records
```

## Requirements

- Python 3.8+
- Flask
- OpenCV
- Face Recognition
- Pandas
- NumPy
- Other dependencies listed in requirements.txt

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Add student face images to the `images` directory
4. Configure attendance CSV files
5. Run the application:
   ```bash
   python app.py
   ```

## Usage

1. Start the application
2. Access the web interface through your browser
3. The system will automatically detect and recognize faces
4. Attendance will be marked automatically
5. View attendance records through the web interface

## Security Features

- Student authentication using DOB verification
- Secure storage of attendance records
- Role-based access control
- Data encryption for sensitive information


