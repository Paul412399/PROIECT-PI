# Multicow cattle pose dataset

Downloaded from Kaggle dataset `twisdu/dairy-cow`, version 1.

Source: https://www.kaggle.com/datasets/twisdu/dairy-cow

This project copy contains only `op_dataset/1980op_dataset`:
- `trainimg/` and `trainjson/`: 1,620 image/Labelme pairs
- `valimg/` and `valjson/`: 180 image/Labelme pairs

The annotations contain 16 points per cow. The point order documented in the Multicow paper is: head, left/right front leg roots, left/right front knees, left/right front hooves, left/right hind leg roots, left/right hind knees, left/right hind hooves, neck, spine, coccyx. The Kaggle dataset page should be checked for its current license/attribution terms before redistribution.

The Multicow annotations are not directly interchangeable with the project's 20-keypoint YOLO model. Any conversion must use an explicit index map and be checked visually against the model's original 20-keypoint schema before training.
