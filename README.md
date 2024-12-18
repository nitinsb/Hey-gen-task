# Face Detection and Clipping Tool

This tool processes a video to detect a reference face, extracts clips containing the face, and outputs metadata.

---

## Setting Up the Environment

1. **Create a Conda Environment**  
   To get started, you can create and activate a Conda environment by running the following commands:

   ```bash
   conda create -n heygen_assignment python=3.10 -y
   conda activate heygen_assignment


## Navigate to the Project Folder

Change to the folder containing the project files using your terminal or command prompt:
  ```bash
  cd /path/to/project/folder
```


## Running the Program

### Using the Makefile

Once inside the project folder, you can run the program by typing the following command in your terminal:

```bash
make
```
This will execute the program with the default arguments for the reference image and video.

## Customizing Arguments
To specify a different video or reference image, modify the make command by adding the desired arguments. For example:

```bash
make ARGS="--video path_to_video --reference path_to_reference_image"

```
## Defaults

Default video path:```./input/video/short.mp4 ```
Default reference image path:```./input/reference/monica.jpeg```

## Reference Image 
![Monica from friends](/input/reference/monica.jpeg)

## Reference Video

![Guess the Scene](input/video/short.mp4)


## Demo Outputs

![Clip-0](output/clip_0.mp4)
![Clip-1](output/clip_1.mp4)








