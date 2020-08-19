# Detecting_Face_Mask
Taking account of nowadays scenario, the face masks are important, and This project helps in detecting whether a person is wearing a face mask or not. This Project is a real time project for detecting face mask on multiple faces at a same time.

## Data: 
The project uses the images as data, and the images consist of faces wearing masks and faces not wearing a mask.

## Model selection:
The model is trained on the above images, and I used MobileNetv2  as my base model for this project.

## Real Time Streaming: 
This project works in real-time. I used my mobile camera with the help of the IP address of my mobile given by the IP webcam app for androids. You can use any of your devices for streaming just by using the IP address.

## Methodology:
I used the pre-trained Caffe model for detecting the faces in the streamed video frame; then these detected faces are feed into our face mask detection model which predicts whether the person in the video stream is wearing a mask or not and accordingly the color of the bounding box around the face changes.
