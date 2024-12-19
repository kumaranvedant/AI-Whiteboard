# AI-Whiteboard
An AI-powered virtual whiteboard that recognizes gestures for real-time drawing and interaction using MediaPipe, OpenCV, TensorFlow, NumPy, and PyTorch

## Features  
- **Real-time Gesture Recognition**: Tracks hand movements and recognizes gestures for drawing, erasing, and selecting shapes.  
- **Scalable and Efficient**: Runs on edge devices like NVIDIA Jetson Orin Nano.  
- **Integration of Multiple Libraries**: Combines MediaPipe, OpenCV, TensorFlow, PyTorch, and NumPy for robust functionality.  

## Technologies Used  
- **MediaPipe**: Hand tracking and gesture recognition.  
- **OpenCV**: Preprocessing video frames and rendering virtual drawings.  
- **TensorFlow & PyTorch**: Gesture recognition using pretrained and fine-tuned models.  
- **NumPy**: Data manipulation and computational operations.  

## How It Works  
1. **Capture Input**: Webcam captures live video frames.  
2. **Hand Tracking**: MediaPipe detects and tracks hand landmarks.  
3. **Gesture Detection**: Models classify gestures based on hand movement and shape.  
4. **Virtual Drawing**: OpenCV visualizes the drawing on a digital canvas.  

