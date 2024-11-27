# Virtual-Mouse-Using-MediaPipe

# Abstract

A gesture-based system using MediaPipe and OpenCV replaces mouse inputs, enabling intuitive, hands-free control for enhanced accessibility.  

# Need for the Project

The need for a gesture-based navigation system stems from the following challenges in traditional human-computer interaction methods:

1. **Accessibility Issues**: Conventional input devices like mice and keyboards may not be suitable for individuals with physical disabilities or in environments where physical contact is not feasible.
2. **Ergonomics**: Prolonged use of mice and keyboards can lead to strain-related injuries such as carpal tunnel syndrome.
3. **Hands-Free Interaction**: Fields like surgery, presentations, or remote operations require seamless interaction without physical contact with devices.
4. **Modern User Experience**: The demand for intuitive, contactless, and futuristic interfaces continues to grow, necessitating innovation in interaction technology.

This project addresses these gaps by providing a hands-free, intuitive, and ergonomic solution that uses real-time hand gesture recognition.

---

# Explanation of the Project

This project introduces a **gesture-based navigation system** that leverages MediaPipe's Hand Landmark and Gesture Recognition models along with OpenCV for real-time processing. It serves as a replacement for traditional mouse inputs, allowing users to interact with a computer using simple hand gestures. Key features include:

### Gesture Mapping to Functions
- **Pinch Right to Left**: Adjust screen brightness.
- **Call Me Sign**: Close application tabs.
- **V Sign**: Navigate the cursor on the screen.
- **Two Fingers Closed**: Perform double-click actions.
- **Close Palm**: Drag and drop items intuitively.
- **ILY Sign**: Simulate the Enter key.
- **Index Extended Sign**: Simulate a right-click.
- **Long Finger Extended Sign**: Simulate a left-click.
- **Pinch Up to Down**: Adjust the volume dynamically.

### Features
- **Real-Time Processing**: OpenCV processes live video input to identify gestures and map them to specific computer functions.
- **High Accuracy**: Gesture recognition is implemented with high precision, enhancing user experience and reliability.
- **Intuitive Interaction**: By mimicking natural gestures, the system bridges the gap between human intuition and computer operations.

### Benefits
This system enhances usability and accessibility while reducing dependency on physical devices. It is particularly valuable in scenarios like medical settings, presentations, and hands-free environments, providing a modern, inclusive, and practical alternative to conventional interaction methods.
