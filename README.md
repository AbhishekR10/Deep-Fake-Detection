# Deep-Fake-Detection
Description:

This Python script is designed for detecting deep fake images by comparing pairs of frames extracted from videos using Mean Squared Error (MSE) and Structural Similarity Index (SSIM).

Prerequisites:

Python 3.x
Required libraries:
  numpy
  matplotlib
  opencv-python (cv2)
  pandas
  mtcnn
  scikit-image (skimage)

Usage:

Place the video files in the directory where this script is located.Modify the extract_multiple_videos function to specify the input video filenames and the output image path.Run the script to extract frames from each video and display them. Press 'q' to quit each video.Use the compare_the_images function to compare pairs of images extracted from different videos.

Functions Provided:

extract_multiple_videos(input_filenames, image_path_infile): Extract frames from multiple input video files.
mean_squared_error(imageA, imageB): Calculate Mean Squared Error (MSE) between two images.
compare_the_images(imageA, imageB, title): Compare two images using MSE and SSIM, displaying results in a figure.
