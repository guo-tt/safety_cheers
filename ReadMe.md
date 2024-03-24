# Safety Cheers

## Object
This work is to detect if worker wear helmet on image and video.

## Creative Points
1. Image dataset is created by Generative AI
2. Negative cases can be generated from positive cases using Grounded SAM
3. Dataset is only 900 images

## Environment

After model trained by YOLO, real-time detection in Gradio UI can be set up in real_time_detection.ipynb under environment super-gradients.yaml

## Code 
1. helmet_gpt4v.ipynb: overall workflow
2. helmet_yolov8_inference.ipynb: interference workflow
3. real_time_detection: ingetration with mac camera


## Future Work
1. GPT4V is not so clever to judge if person wear helmet if the person is not showing face or wearing mask
2. How to validate the labeling correctness
3. Other PPE detection
4. Danger environment detection