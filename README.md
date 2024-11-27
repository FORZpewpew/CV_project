# Parking Lot Free Places Detection

This project aims to develop a solution for identifying empty parking spaces in parking lots. It utilizes YOLO model to analyze images and detect available spaces. However, this approach struggles with generalization and requires hundreds of images from a specific parking lot to achieve reliable results.

You can test any model using any weights from the tests folder in the second-to-last cell of the main.ipynb notebook using the images provided in the demo_images folder. While the model has not specifically seen these images, it was trained on the same parking lots, resulting in fairly accurate detections.

Additionally, you can test the model on your own parking lot image in the last cell of the main.ipynb file. However, please note that the results are unlikely to be meaningful.