
## Object Detection App with Streamlit and DDN Model in OpenCV

This application demonstrates real-time object detection using the Deep Neural Network (DDN) model within OpenCV and a user-friendly interface built with Streamlit.

**Features:**

-   **Real-time object detection:** The app detects objects from uploaded images.
-   **DDN model:** Utilizes a pre-trained DDN model for efficient object classification. (Specify the DDN model you're using here)
-   **Streamlit interface:** Provides a clear interface for  image upload, and detected object visualization.

**Requirements:**

-   Python 3.x ([https://www.python.org/downloads/](https://www.python.org/downloads/))
-   OpenCV ([https://opencv.org/](https://opencv.org/))
-   Streamlit ([https://docs.streamlit.io/](https://docs.streamlit.io/))
-   Pre-trained DDN model weights (in **model.py**)

**Installation:**

1.  Clone this repository or download the files.
    
2.  Install required libraries:
    
    Bash
    
    ```
    pip install opencv-python streamlit
    
    ```
    
    
    

    

**Usage:**

1.  Run the app:
    
    Bash
    
    ```
    streamlit run app.py
    
    ```
    

   2.  Select your image source (file in jpg, png,.. format) using the Streamlit interface.
    
3.  The app will display the uploaded image with detected objects labelled on top.
    

**Explanation:**

-   **main.py:** This script contains the core logic of the app.
    -   Imports necessary libraries (OpenCV, Streamlit).
    -   Loads the pre-trained DDN model weights.
    -   Creates a Streamlit layout with options for image upload.
    -   Reads uploaded images.
    -   Performs object detection using the DDN model on each frame/image.
    -   Draws bounding boxes and labels for detected objects on the image.
    -   Displays the processed image in the Streamlit app.
- **model.py**: Contain the DDN models's settings
**Customization:**

-   You can experiment with different DDN models for various object detection tasks. (Provide guidance on model selection)
-   The code can be extended to display additional information like confidence scores for detected objects.
