# Virtual-Presentation

A presentation control system that detects hand gestures to navigate and annotate slides using Python and OpenCV.

<img width="635" alt="VP1" src="https://user-images.githubusercontent.com/67221447/228813261-b48c7ca3-2bb8-481b-802d-f3e8b680c211.png">
<img width="624" alt="VP2" src="https://user-images.githubusercontent.com/67221447/228813279-a0bb203e-ad42-4b6e-b396-5fc854e31343.png">

### Project Objectives:
- An enhanced hand gesture-based virtual presentation tool 
- Adds finger tracking controlled air drawing/annotation capability
- Gesture based controls like switching slides, activating drawing tool, erasing etc.

### Gesture-based Functionalities:
- Gesture 1: Slide to Previous Slide [1, 0, 0, 0, 0]
- Gesture 2: Slide to Next Slide [0, 0, 0, 0, 1]
- Gesture 3: Activate Pointer [0, 1, 1, 0, 0]
- Gesture 4: Draw Pointer [0, 1, 0, 0, 0]
- Gesture 5: Erase Latest Drawing [0, 1, 1, 1, 0]

### Worflow Diagram

