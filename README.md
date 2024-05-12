# Yoga Pose Visual Assistant

## Usage

1. First, ensure you have the necessary dependencies installed.
2. Clone this repository or download the notebook.
3. Open the notebook in your preferred Python environment.
4. Run the cells in the notebook sequentially.

## Features

- **Pose Detection**: Utilizes MediaPipe to detect and track human poses from images or video streams.
- **Angle Calculation**: Calculates specific angles between body landmarks to determine pose correctness.
- **Feedback System**: Provides real-time feedback on detected poses, highlighting correct and incorrect yoga poses.
- **Yoga Pose Recognition**: Identifies and labels specific yoga poses based on detected body angles.

## Functionality

The notebook includes functions for:
- Extracting landmark points from detected poses.
- Calculating angles between body landmarks.
- Identifying and labeling specific yoga poses based on angle criteria.

## To Do:
- [ ] 1. Capture the joints angle and train a DNN on it.
- [ ] 2. Add more poses.
- [ ] 3. Deploy it using TF-JS.

### Known Issues (Work In Progress ...)
- In some cases, the pose detection may fail to recognize certain poses accurately, leading to incorrect feedback.

### Test Output
https://user-images.githubusercontent.com/90381570/185234179-bf4ad0c0-734f-42e0-ae05-de3de36c3e85.mp4

@Original Video source : https://www.youtube.com/watch?v=QVEINjrYUPU

## License
This project is licensed under the [MIT License](LICENSE).
