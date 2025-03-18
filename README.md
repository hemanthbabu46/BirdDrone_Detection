## BirdDrone: A Solution for Airspace and Wildlife Security

### Project Overview

BirdDrone is a deep learning-based system designed to detect and classify drones and birds in real-time. Utilizing advanced object detection techniques like **YOLO** (You Only Look Once) and **Faster R-CNN**, along with the tracking algorithm **DeepSORT**, BirdDrone aims to enhance airspace security, wildlife conservation, and surveillance.

---

### Key Features

- **Real-Time Detection:** Identifies and classifies drones and birds in real-time with a detection precision of 0.93.
- **Interactive Web Application:** Developed using **React** for the frontend and **Flask** for the backend.
- **Multiple Detection Models:** Combines **YOLO** for rapid detection and **Faster R-CNN** for higher accuracy.
- **Efficient Tracking:** Uses **DeepSORT** for persistent tracking in dynamic environments.
- **Use Cases:** Aviation safety, wildlife conservation, monitoring restricted airspace, and agricultural surveillance.

---

### Project Phases

#### Data Collection

- Sourced from **Roboflow** ([Dataset Link](https://universe.roboflow.com/h-ksv6g/drone_bird-hoizd-cudub)), containing labeled instances of birds and drones.

- Sourced from **Roboflow**, containing labeled instances of birds and drones.

- Diverse dataset with varying environmental conditions to enhance model robustness.

#### Data Preprocessing

- Image resizing, normalization, and augmentation.
- Removal of noise and artifacts to improve model performance.

#### Model Development

- **YOLO**: Fast object detection for real-time surveillance. [YOLO Model Training Link](https://colab.research.google.com/drive/1VJxEYe1uOVOjw2RG-S6anLeJS1E6tOOV#scrollTo=YeLRjd8s88x6)

- **Faster R-CNN**: High-accuracy detection for challenging environments. [Faster R-CNN Model Training Link](https://colab.research.google.com/drive/1VlURfaF8q17RNHT1ExxBqYONCxpPpi6X#scrollTo=cXhOUHFzEtgY)

- **DeepSORT**: Tracks detected objects, maintaining identities across frames.



#### Deployment

- **Frontend**: React for a dynamic and user-friendly interface.
- **Backend**: Flask for model serving and API communication.

---

### Installation & Setup

1. **Clone the Repository:**

```bash
 git clone https://github.com/your-repository/BirdDrone.git
 cd BirdDrone
```

2. **Install Dependencies:**

```bash
pip install -r requirements.txt
```

3. **Run the Application:**

```bash
# Start the backend server
python server.py

# Start the frontend
cd frontend
npm install
npm start
```

---

### How to Use

- Upload an image or video file through the web interface for detection.
- Select detection type: **Bird**, **Drone**, or **Both**.
- Real-time detection results will appear with bounding boxes and labels.
- Use the camera mode for live detection.

---

### Future Scope

- Integrating more advanced detection models like **BERT** for enhanced NLP-based analysis.
- Implementing multi-language support.
- Scaling to handle larger datasets and real-world applications.

---

### Contributors

- G. Hemanth Babu
- K. Aditya Mahaan
- K. Uday Kiran
- M. Srujan



