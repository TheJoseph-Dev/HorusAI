# HorusAI

<p align="center">
  <img src=".github/image1.png" alt="Logo" width="200">
</p>

An iOS app designed to help visually impaired people understand their surroundings.

The app concatenates many AI models in a pipeline in order to obtain audible description of the environment.

Pipeline:
- YOLO: Identifies objects in real-time captured by the camera.
- Gemini: Interprets YOLO's data and outputs a text description on how the surronding might be.
- Text2Speech: Uses AI voice to inform the user by using the Gemini generated text. 

*This project was developed during IBM Hackatruck event by me and my group in 2025*

## Screens

**Main screen**
<p align="center">
  <img src=".github/image4.png" alt="Main Screen" width="200">
</p>

**Config screen**
<p align="center">
  <img src=".github/image5.png" alt="Main Screen" width="200">
</p>

**Info screen**
<p align="center">
  <img src=".github/image6.png" alt="Main Screen" width="200">
</p>

**Camera screen**
<p align="center">
  <img src=".github/image10.png" alt="Main Screen" width="200">
</p>

---