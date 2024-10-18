# Tasle, Car and Line Detection in Videos

## Required Dependencies

To run this project, you need to install the following Python packages:

```bash
!pip install opencv-python
!pip install moviepy
```

## Background and Motivation

Tasle provides a solution for detecting cars and road lines in a video. The project simulates some fundamental principles of self-driving car technology. By processing a recorded video of a road trip, the repository aims to highlight how computer vision can be applied to real-world scenarios.

You can access the video used for this project [here]([insert_link_to_video](https://drive.google.com/file/d/1VrFB6E6vBjlCYJNyJ7xty-ogqFvidowH/view?usp=drive_link.)).

The project is designed to run in Google Colab, where you can easily mount your Google Drive to access video files.

## Running the Project

To run the notebook, follow these steps:

1. **Mount Your Google Drive**: This allows the notebook to access video files stored in your Drive.
2. **Execute the Notebook**: Run the cells in the notebook sequentially. The code will process the input video and detect cars and road lines.
3. **Output**: After processing, an MP4 file will be generated, showcasing the detected car bounding boxes and road lines. This output video will be saved back to your Google Drive.

## Results

[Output]([insert_link_to_video](https://drive.google.com/file/d/1-9QLnZQL827H5QVdo7ejGezdWx2Im1Fy/view?usp=sharing))

After running the notebook, you will have an output video that clearly shows:
- Bounding boxes around detected cars.
- Highlighted lines on the road.

This visual representation serves as a basic illustration of how computer vision can assist in autonomous vehicle navigation.
