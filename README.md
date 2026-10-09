
# 🛡️ AI Guardian — Digital Content Protection System

AI Guardian is an individual AI-powered project focused on identifying and helping protect digital visual content. It explores image fingerprinting, perceptual hashing, face detection, and database-based record management to support the identification of potentially duplicated or matching content.

The project is currently under development, with the long-term goal of exploring broader digital content monitoring and protection.

## 🎯 Objectives

- Identify exact file matches using SHA-256 hashing.
- Explore visual similarity detection using perceptual hashing (pHash).
- Detect faces in images using computer vision techniques.
- Store image records and ownership information in SQLite.
- Develop image and video processing workflows.
- Explore future monitoring, alerts, and reporting capabilities.

## ✨ Features

### 1. SHA-256 Hashing
Generates cryptographic fingerprints to help identify files with identical contents.

### 2. Perceptual Hashing (pHash)
Explores image similarity detection beyond exact file matching.

### 3. Face Detection
Uses image-processing techniques to locate faces in images.

### 4. SQLite Database
Stores image-related records, including image names, hashes, owner information, and upload timestamps.

### 5. Image and Video Processing
Includes image-processing functionality and ongoing work on video-processing workflows.

> **Note:** Automatic internet monitoring, notifications, and complete video protection are planned or under development, not claimed as completed features.

## 🧰 Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core development |
| OpenCV | Image processing and face detection |
| SHA-256 | Exact file fingerprinting |
| Perceptual Hashing | Visual similarity exploration |
| SQLite | Local database storage |
| Git & GitHub | Version control |
| VS Code | Development environment |

## ⚙️ How It Works

1. Provide an image to the local processing workflow.
2. Generate a SHA-256 fingerprint.
3. Generate a perceptual hash where supported.
4. Detect face regions when required.
5. Store or retrieve image records using SQLite.
6. Compare fingerprints to investigate potential matches.

## 📁 Project Structure

```text
AI-Guardian/
├── datasets/
│   └── test_videos/
├── tests/
│   └── test_video_processor.py
├── guardian.db
├── requirements.txt
└── README.md
```

*This is an illustrative structure; adjust it to match your actual repository files.*

## 🚀 Installation and Setup

### Prerequisites

- Python 3.13 or a compatible version
- Git
- Visual Studio Code

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-Guardian.git
cd AI-Guardian
```

Replace `YOUR-USERNAME` and the repository name with your actual GitHub details.

### Step 2: Create a Virtual Environment

**Windows PowerShell:**

```powershell
py -3.13 -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### Step 3: Install Dependencies

If your project contains `requirements.txt`, run:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Step 4: Run the Project

Run the actual Python entry-point file in your repository:

```bash
python your_entry_point.py
```

Replace `your_entry_point.py` with the correct filename.

## 🧪 Testing

The project has included development and testing work involving:

- SHA-256 and perceptual hash generation.
- Image processing and face detection.
- SQLite record storage.
- Video-processing test workflows.

Ensure all required test images and videos exist at their expected paths before running tests. End-to-end video processing still requires successful validation.

## 🔮 Future Enhancements

- [ ] Complete and test video processing.
- [ ] Add GIF processing and frame-level comparisons.
- [ ] Improve image similarity matching.
- [ ] Explore face-encoding-based matching.
- [ ] Investigate invisible watermarking.
- [ ] Develop a dashboard for scan results and reports.
- [ ] Explore supported-source monitoring and match notifications.
- [ ] Add automated tests and stronger data protection.

## 📚 Learning Outcomes

- Python-based image processing.
- Cryptographic and perceptual hashing.
- Computer vision fundamentals.
- SQLite database operations.
- Testing and debugging.
- Designing an AI-based digital content protection workflow.

## 👩‍💻 Author

**Avantika Kashyap**

B.Tech Computer Science and Engineering  
Specialization: Artificial Intelligence and Machine Learning  
Haridwar University

## ⚠️ Disclaimer

AI Guardian is an educational project under development. Hashing, face detection, and database records do not independently prove ownership or guarantee detection or prevention of unauthorized content use. Production-level monitoring and protection require further implementation, testing, and validation.
