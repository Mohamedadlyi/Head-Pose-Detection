# Head Pose Detection using Supervised Machine Learning

Head pose detection using supervised machine learning techniques. The models are based on face detection algorithms and landmarks extracted using Mediapipe. The notebooks focus on using only the x and y values of landmarks for training and testing.

## Notebooks:

1. **head-pose-estimation.ipynb**: This notebook outlines the process of training a head pose detection model using the AFLW2000-3D dataset. It covers:
   - Data preprocessing, including face detection and landmark extraction using Mediapipe.
   - Feature engineering, extracting relevant features (x, y values of landmarks).
   - Model selection and training, evaluating various algorithms to determine the best-performing one.
   - Model evaluation, assessing the performance of the selected algorithm.

2. **Head-Pose-Detection-videos.ipynb**: This notebook demonstrates how to use the trained head pose detection model to process a video. It includes:
   - Loading the pre-trained model.
   - Estimating head pose information (yaw, pitch, roll) from the video frames.
   - Annotating the original video with the head pose information.
   - Generating a new video with the original and annotated videos side by side.

## Data:
- AFLW2000-3D Dataset: [Link](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/main.htm)

## Dependencies:
- Python 3
- Jupyter Notebook
- Mediapipe
- OpenCV (cv2)
- moviepy
- scikit-learn
- FFmpeg
  
## Availability:

This project is available on Kaggle, where additional datasets for testing purposes are provided.

- Kaggle Repository: [Link](https://www.kaggle.com/code/mohamedadlyi/head-pose-estimation)


Users can access the project on Kaggle for experimentation with additional datasets and testing.

## License:
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
