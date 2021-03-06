# Instance Segmentation using a Tkinter-based interface
This project detects individual elements in an image and renders a bounding box or a mask over the detected elements in the image.

## Dependencies
1. PyTorch
  `pip3 install torch torchvision torchaudio`
2. Numpy
  `pip3 install numpy`
3. Matplotlib
  `pip3 install matplotlib`
4. Pillow
  `pip3 install pillow`
5. mypackage-rv4102
  `pip3 install ./my_package_rv4102-0.0.1-py3-none-any.whl`

## Notes
1. This software determines only the top 3 entities in the given image based on a confidence score. Other detected entities are not covered by segmentation masks or bounding boxes.
2. Temporary image files (1 for bounding box and 1 for segmentation mask) are saved to disk in the working directory during the runtime of the script. It is destroyed automatically afterwards.

## Screenshots
1. ![error](/A4/Screenshots/error.png)
2. ![bbox1](/A4/Screenshots/bbox1.png)
3. ![mask1](/A4/Screenshots/mask1.png)
4. ![bbox2](/A4/Screenshots/bbox2.png)
5. ![mask2](/A4/Screenshots/mask2.png)
