# Computer-Vision

Computer Vision Starter Projects
A collection of Google Colab-compatible Python scripts for common Computer Vision tasks.
🚀 Projects Included
1. Image Classification (MobileNetV2)
Uses a pre-trained MobileNetV2 model (trained on the ImageNet dataset) to identify objects within an image.
Key Libraries: tensorflow, keras.
Functionality: Resizes input to 224x224, pre-processes pixels, and returns the top 3 predicted labels with confidence scores.
2. Image Cartoonizer
Transforms a standard photograph into a cartoon-like illustration.
Technique: Uses medianBlur for smoothing, adaptiveThreshold to extract bold edges, and bilateralFilter to flatten colors while preserving detail.
3. Number Plate Detection
A geometric approach to finding vehicle license plates.
Technique: Uses Canny Edge Detection and contour approximation. It searches for 4-sided polygons (rectangles) among the largest contours in the image.
4. Face Mask Detection (Haar Cascades)
Detects faces in a frame and applies a bounding box.
Technique: Utilizes the haarcascade_frontalface_default.xml classifier to identify facial features and overlays a "Mask?" status indicator.
5. Color Channel Separation (RGB Split)
Visualizes how an image is constructed across different color planes.
Functionality: Splits a standard BGR image into individual Red, Green, and Blue intensity maps.
