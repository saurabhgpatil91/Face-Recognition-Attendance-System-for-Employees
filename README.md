# Face Recognition Attendance System for Employees

A Python-based attendance management system that automatically marks employee attendance using real-time face recognition.

## Features

- Employee face registration
- Face encoding and training
- Real-time face recognition
- Automatic attendance marking
- CSV attendance records
- OpenCV webcam support
- Easy to extend with database integration

## Technologies Used

- Python 3.10+
- OpenCV
- face_recognition
- NumPy
- Pandas
- dlib

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/face-recognition-attendance-system.git

cd face-recognition-attendance-system
```

Install dependencies

```bash
pip install -r requirements.txt
```

## Usage

### Step 1: Capture Employee Images

```bash
python src/capture_faces.py
```

### Step 2: Train Face Encodings

```bash
python src/train_model.py
```

### Step 3: Start Attendance System

```bash
python main.py
```

Attendance will be stored in:

```
attendance/Attendance.csv
```

## Folder Structure

```
data/
attendance/
src/
screenshots/
```

## Future Improvements

- MySQL Database
- Flask Web Dashboard
- Employee Login
- Admin Panel
- Email Reports
- QR Code Backup Attendance
- Cloud Deployment

## License

MIT License
