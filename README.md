# EcoSense

## Overview
EcoSense is a project aimed at identifying instances of public littering or waste disposal in public spaces. Using the YOLOv5 object detection model, this system can detect when individuals litter and provide details such as the time of the littering event in sample videos. The ultimate goal is to implement this system in CCTV cameras to create a cleaner environment and raise awareness about the importance of not littering in public places.

## Running in Google Colab

### Colab link : [Click here](https://colab.research.google.com/drive/158z1gYxkf32Zpm5riJBayh4NyeDwX9Cb?usp=sharing)


### Usage
1. Open the Colab notebook  in Google Colab.
   
2. The notebook will first download sample videos for demonstration purposes.

3. Next, it will install the required Python libraries and download the YOLOv5 model.

4. A function is defined to display the available sample videos to the user in an HTML window.

5. You can then select a video from the list displayed.

6. The main function will process the selected video and identify instances of littering, providing timestamps for each event.

7. The results will be displayed in the notebook, showing the detected instances of littering along with the corresponding timestamps.

### Sample Video
 sample videos (`video_!.mp4`) to (`video_9.mp4`) is provided in the Colab notebook for testing purposes. You can select one of the video to see how the detection works.

### Viewing the Results
The notebook will output the detected instances of littering along with the corresponding timestamps. You can find this information displayed directly in the notebook after running the detection on the selected video.

### License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/Senthilsk10/Ecosense/blob/main/LICENSE) file for details.

### Acknowledgments
Special thanks to the developers of YOLOv5 for their excellent object detection model.

[View Licence](https://github.com/Senthilsk10/Ecosense/blob/main/LICENSE)
