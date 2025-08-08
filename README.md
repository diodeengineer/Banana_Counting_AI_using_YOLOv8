# Banana_Counting_AI_using_YOLOv8



A web-based AI tool to detect and count bananas in images using a custom-trained YOLOv8 model. Built with a React frontend and a Python/Node.js backend (in progress).

## 🚀 Project Overview

- 🔍 **Detection Model**: YOLOv8, trained on custom banana images in kaggle notebook.
- 📤 **Input**: Users upload images through the web interface.
- 📊 **Output**: The number of bananas detected.

## 🧠 Model Info

- Trained using [Ultralytics YOLOv8](https://docs.ultralytics.com).
- Sample weights: `bestbanana.pt` included.

## 🖼️ Sample Output

![sample](assets/sample_output.png) <!-- Add your own image -->

## 🧰 Tech Stack (Planned)

| Layer        | Tech Options        | Status     |
|--------------|---------------------|------------|
| Frontend     | React (with Vite) | ✅ Planned |
| Backend      | Flask or Node.js    | 🛠️ In Progress |
| Deployment   | TBD (Render, Vercel, etc.) | 🛠️ Soon |



## 🛠️ Local Setup

```bash
# Clone this repo
git clone https://github.com/diodeengineer/Banana_Counting_AI_using_YOLOv8
cd Banana_Counting_AI_using_YOLOv8

# Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run backend server (example with Flask)
python backend/app.py
```

