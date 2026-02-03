# Lab_Task_04_DIP

# *Task 04: Histogram Equalization and Contrast Enhancement with Histogram Comparison*

*Roll Number:* 2023-SE-02

### *Prompt*

*"Write a Python program using OpenCV, NumPy, and Matplotlib in Google Colab to perform histogram equalization and contrast enhancement on a colored image uploaded by the user. The program should do the following steps:

* Allow the user to upload any image.
* Display the original image.
* Apply built-in histogram equalization on the Y channel for color images and display the result.
* Implement manual histogram equalization on the grayscale version of the image, display the result, and use it for histogram comparison.
* Apply contrast stretching on the grayscale image and display the result.
* Apply logarithmic transformation on the grayscale image and display the result.
* Apply gamma transformation (with gamma=0.5) on the grayscale image and display the result.
* Display all transformed images side by side in a single figure with proper titles and axes turned off.
* Plot histograms for Original, Manual Equalized, and Built-in Equalized images side by side for comparison.
* Ensure the code is well-structured, modular, clean, and fully compatible with Google Colab, with each step clearly labeled and visually organized."*

---

## *Objective*

The objective of this task is to enhance image quality using *histogram equalization* (both built-in and manual) and various *contrast enhancement techniques*, and to compare the results visually and through histograms. This helps understand how different enhancement methods affect grayscale and color images.

---

## *Methodology / Approach*

1. Upload the colored image in Google Colab using files.upload().
2. Display the *Original Image*.
3. Apply *built-in histogram equalization* on the *Y channel* of the color image and display the enhanced image.
4. Implement *manual histogram equalization* on the grayscale version, display the result, and prepare it for histogram comparison.
5. Apply *contrast stretching* on the grayscale image to expand intensity range.
6. Apply *logarithmic transformation* to enhance darker regions.
7. Apply *gamma transformation* with gamma = 0.5 to adjust brightness non-linearly.
8. Display all transformations (*Original Grayscale, Manual Equalized, Built-in Equalized, Contrast Stretching, Log Transform, Gamma Transform*) side by side.
9. Plot histograms for *Original, Manual Equalized, and Built-in Equalized* images side by side for comparison.

---

## *Results / Observations*

* *Built-in histogram equalization* enhances color contrast effectively using the luminance channel.
* *Manual histogram equalization* produces similar enhancement and helps understand the step-by-step process.
* *Contrast stretching* improves intensity range, making details in the grayscale image clearer.
* *Logarithmic transform* brightens dark regions while maintaining overall contrast.
* *Gamma transform (γ=0.5)* increases brightness non-linearly, enhancing visibility in darker areas.
* Histogram comparison clearly shows how manual and built-in equalization redistribute pixel intensities.
* Side-by-side display allows visual comparison of all transformations and their impact.

---

## *Tools and Libraries Used*

* *Python 3.x*
* *OpenCV (cv2):* Image reading, conversion, histogram equalization
* *NumPy (np):* Manual histogram computation and array operations
* *Matplotlib (plt):* Visualization of images and histograms
* *Google Colab:* Image upload and execution environment
