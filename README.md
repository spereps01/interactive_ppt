# Hand Gesture Controlled Presentation

## Description

This project allows for controlling a presentation using hand gestures via a camera. The possible gestures are as follows:

- Moving the open palm to the right: advances to the next slide.
- Moving the open palm to the left: goes back to the previous slide.
- Raising the index finger: activates the pointer.
- Moving the index and middle fingers within a defined area: underlines.
- Raising the thumb: erases.

Additionally, once the Python application is launched, the user can select which PowerPoint presentation to open from their documents on the computer.

## Execution

To install the necessary libraries from the terminal, execute the following command:

```bash
pip install -r requirements.txt
```

To start the project, run the following command in the terminal:

```bash
python main.py
```

If you want to add another presentation, replace the 'Presentation' folder by inserting your PowerPoint in .png format.

## Author

- Francesco Maria Longobardi
- Simone Giovagnoni
- Giuseppe Carnicella
