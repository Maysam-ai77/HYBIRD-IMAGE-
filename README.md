# Hybrid Image Generation using OpenCV

This project demonstrates how to create a **hybrid image** by combining the high-frequency details of one image with the low-frequency features of another.
The result is an image that changes itsappearance depending on the viewing distance — a classic technique in image processing and computer vision.

## Idea Behind the Project

By blending:
- **High-frequency components** (edges and fine details) from one image.
- **Low-frequency components** (smooth shapes and shadows) from another image.

We get a hybrid image that looks like one person up close and another person from afar.

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- **Google Colab** (as the development environment)

## How It Works

1. Load two grayscale images.
2. Apply a **Gaussian Blur** to one image to extract low-frequency details.
3. Subtract a blurred version of the other image to obtain high-frequency details.
4. Merge both using `cv2.addWeighted()` to form a hybrid image.
5. Visualize the results using `matplotlib`.

## Files

- `woman_faces.jpg`: Image used for high-frequency features.
- `man_faces.jpg`: Image used for low-frequency features.
- `Untitled20.ipynb`: The main Colab notebook.
- `hybrid_image.jpg`: The final result image.

## Output

The output shows:
- **Image 1**: High-frequency details
- **Image 2**: Low-frequency image
- **Hybrid Image**: A combination of both

## Author

This project was created by **Maisam**, a student of Artificial Intelligence at Al-Zaytoonah University of Jordan, using **Google Colab** as a practical application of image processing techniques.

---
