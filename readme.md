# Invisibility Cloak using OpenCV

This project demonstrates how to create an invisibility cloak effect using OpenCV library in Python. The effect is achieved by capturing video from a webcam and applying image processing techniques to make a selected color range appear transparent.

## Prerequisites

- Python 3.x
- OpenCV library

## Installation

1. Clone this repository:

    ```
    git clone https://github.com/Yuval728/invisibility-cloak.git
    ```

2. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Run the `invisibility_cloak.py` script:

    ```
    python invisibility_cloak.py
    ```

2. When the webcam window opens, select the color of the cloak by adjusting the trackbars.

3. Place the cloak in front of you and see the magic happen!

## How it works

The script captures video frames from the webcam and converts them from the RGB color space to the HSV color space. It then applies a mask to the frames to extract the selected color range. Finally, it blends the masked frames with the original frames to create the invisibility cloak effect.


<!-- ## License

This project is licensed under the [MIT License](LICENSE). -->
