<h2 align="center">
  Virtual Mouse
</h2>

<div align="center">
  <img src="https://img.shields.io/badge/python-v3.7.13-blue.svg"/>
  <img src="https://img.shields.io/badge/mediapipe-v0.9.0.1-blue.svg"/>
  <img src="https://img.shields.io/badge/PyAutoGUI-v0.9.53-blue.svg"/>
</div>

This is virtual mouse python code using mediapipe library and PyAutoGUI library.

<div align="center">
<img src="assets/images/virtual_mouse.gif" width="70%">
</div>

The gesture of a single hand is used and when only one finger is spread, it is in Moving mode, and when two fingers are joined, a Click is performed.

## Requirements

- mediapipe
- pyautogui



You can install it from PyPI:

```sh
pip install mediapipe
pip install pyautogui
```

### Mediapipe

[Mediapipe](https://google.github.io/mediapipe/) is an open-source framework for building multimodal (eg. video, audio, etc.) applied ML pipelines. It provides a way to develop, test, and deploy machine learning models for various applications like hand tracking, object detection, and more. With Mediapipe, you can build custom pipelines using a set of pre-existing components, as well as create new ones. The framework is optimized for real-time performance on mobile, desktop, and cloud platforms.

### PyAutoGUI

PyAutoGUI is a Python module for programmatically controlling the mouse and keyboard. It allows you to automate mouse clicks, movements, and scrolling. You can also simulate keyboard input and manage windows. PyAutoGUI is useful for automating repetitive tasks and for testing GUI applications. It works on Windows, macOS, and Linux.