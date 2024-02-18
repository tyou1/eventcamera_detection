# EventCamera Spacecraft Detection
- **Bonus project for Space Mission Design WS 2023 at TUM**
- **Goal**: Using ML techniques, use image processing for automatic identification of satellites given video of spacecrafts in orbit




<div style="display: flex;">
  <img src=".github/satellite.jpeg" alt="image 1" style="margin-right: 20px;" height="250"/>
  <img src=".github/demo.png" alt="image 2" style="margin-left: 20px;" height="250"/> 
</div>

(Image Source: Valispace)

# What's in this repository
  In the `pipeline` folder, it contains:
  - `output_1.avi`: Given video from an event-based camera.
  - `pipeline_v2.ipynb`: Jupyter Notebook containing the pipeline. 
  - `detection_coordinates.txt`: Output file containing all detection coordinates.
  - `Eventcamera_detection`: Annotated output video with delineated detections.
  - Some other intermediary files.



# How to run locally
- Install all Python dependencies, specified in `requirements.txt`: <br>
`pip install -r requirements.txt`
- In case of new test videos or rerun of the results, in the folder just keep the new video and the `pipeline_v2.ipynb` with the environment installed in `requirements.txt`.

