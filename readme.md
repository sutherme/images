# Facial Recognition on Raspberry Pi with AWS Rekognition 

Use cameras on [Raspberry  Pi](https://www.raspberrypi.org/) to take photos and match the recorded faces with indexed faces on [Amazon Rekognition](https://aws.amazon.com/rekognition/).

## Basic Usage
1. Upload recognized photos and names to [S3](https://aws.amazon.com/s3/).
2. [Index faces](https://github.com/xbwei/data-analysis-aws/blob/master/facial-recognition-raspberry-pi/index_faces.py) on the uploaded photos with AWS Rekognition.
3. Use cameras on Raspberry Pi to record photos in real time.
4. The [python code](https://github.com/xbwei/data-analysis-aws/blob/master/facial-recognition-raspberry-pi/match_faces.py) will match the faces on the recorded photos to the indexed faces, and similarities will be reported. 

## Demo Video
https://www.youtube.com/watch?v=xFCK1-lYzqA
