# VISION 👀
VISION stands for "Visually Intelligent System for Identifying Objects in Nature." It is a Multiple Object Detection Web Application powered by Python, Streamlit, and YOLOv5.

# Installation 💻

1. Clone the repository:
- `git clone "https://github.com/EJD222/vision-app.git"`

2. Navigate to the newly created folder:
- cd `vision-app` or `<file-name>`

3. Create a virtual environment using either conda or python venv:
- Using Linux:
    - `conda create -n envyolov5 pip python=3.9` or `conda create -n envyolov5`
    - `source envyolov5/bin/activate`
- Using Windows:
    - `python -m venv envyolov5`
    - `.\envyolov5\Scripts\activate` or `conda activate envyolov5`

4. Install the required packages by running:
- Using Linux:
    - `bash ./yolov5setup.sh`
- Using Windows:
    - `python ./yolov5setup.py`

* If any "module not found" errors occur, install the relevant modules using pip install <module_name>.

5. Navigate to the yolov5 directory:
- `cd yolov5`

6. Run the Streamlit app:
- `streamlit run app.py`

7. Exit the Streamlit app:
- `Ctrl + C`

- Error handling: 
    - After running the above script,  if `no module error` is occured then just find the relevent `pip install <module name>` command and run it
- Other useful commands
    - `conda env list`
    - `conda env remove -n ENV_NAME`
    - `conda list`
    - `python.exe -m pip install -r tfod1_requirements.txt --user`