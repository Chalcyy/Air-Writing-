# ✋ Gestures! – Air Drawing with Hand Tracking

Gestures! is an interactive project that lets you **draw and erase in the air** using only your hand gestures. Powered by **MediaPipe Hands ML model**, it delivers real-time fingertip tracking and gesture recognition for a touchless creative experience.

---

## 🚀 Key Features

### ✏️ Drawing Mode
- Raise only your **index finger** to draw in the air  
- Smooth line tracking follows your fingertip  
- Customizable colors and brush sizes  
- Real-time visual feedback with a cursor  

### 🧹 Erase Mode
- Raise **all 5 fingers** to erase  
- Circular eraser follows your hand  
- Removes drawn content where you point  

### 🎯 Advanced Hand Tracking
- Uses **MediaPipe Hands ML model** for accurate finger detection  
- Detects individual finger positions in real-time  
- Distinguishes between different hand gestures  
- Works with just one hand  

### 🎨 Interactive Controls
- Choose any color for drawing  
- Adjust brush size (2–20px)  
- Clear canvas with one click  
- Download your air drawing as **PNG**  

### 💡 Smart Gesture Recognition
- **Index finger only** → Drawing mode (other fingers curled)  
- **All 5 fingers extended** → Erase mode  
- **Other gestures** → Idle mode (no drawing/erasing)  

---

## 🖥️ How It Works
1. Click **Start Camera** to begin  
2. Allow webcam access when prompted  
3. Show your hand to the camera  
4. Point with **index finger only** to draw  
5. Open **all fingers** to erase  
6. Change colors and brush size anytime  

---

## ⚙️ Under the Hood
Gestures! uses **MediaPipe’s state-of-the-art hand tracking ML model** to detect **21 hand landmarks** in real-time. This enables:
- Precise fingertip tracking  
- Reliable gesture recognition  
- A seamless touchless interactive experience  

---

## 📦 Installation & Setup
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/gestures.git
cd gestures
npm install
npm start
