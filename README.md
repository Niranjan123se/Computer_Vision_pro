**This model is not up to the production standards**

---

**Project Description:**

In this computer vision project, we've developed a Python application for X-ray image segmentation. The application takes an input folder containing X-ray images and automatically isolates various organs and structures, including the heart, lungs, ribcage, diaphragm, and lower thoracic region. 

**How to Use:**

1. Clone the repository to your local machine.
2. Navigate to the project directory.

**Installation:**

Before running the application, ensure you have the required libraries installed:

- opencv-python-headless
- numpy
- pandas
- ultralytics

You can install them using pip:

```
pip install opencv-python-headless numpy pandas ultralytics
```

**Running the Application:**

Modify the following paths in the `main4.py` file:

- `model_folder`: Folder containing YOLOv8 model weights for segmentation.
- `image_path`: Path to the input X-ray image.
- `output_folder`: Output directory for segmented images.

After configuring the paths, run the application using:

```
python main4.py
```

The application will create subfolders for each segmented object in the output directory.

**Customization:**

To segment specific objects, replace or update the YOLOv8 model weights in the `model_folder`. No code changes are required.

**Project Flow:**

1. Annotated X-ray images with various objects.
2. Created a Python script to extract individual objects from JSON files.
3. Trained the YOLOv8 model on annotated data to obtain required weights.
4. Developed the automated segmentation application (main4.py).

**Contributors:**

Niranjan Kulkarni
kulkarniniranjan40@gmail.com

**License:**

This project is licensed under the afl-3.0 License. (You can use it for you research and acadmic prject.)

---
