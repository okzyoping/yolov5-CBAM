# YOLOv5-CBAM

Tested on Ubuntu 20.04

## Setup Environment

1. Update package index:
    ```bash
    sudo apt update
    ```

2. Upgrade installed packages to latest versions:
    ```bash
    sudo apt upgrade
    ```

3. Install virtualenv:
    ```bash
    sudo apt install virtualenv
    ```

4. Create a virtual environment (replace 'your_name_environment' with your desired environment name):
    ```bash
    virtualenv -p /usr/bin/python3 your_name_environment
    ```

## Activate Environment

1. Activate the virtual environment:
    ```bash
    source your_name_environment/bin/activate
    ```

## Clone Repository & Install Dependencies

1. Clone the repository:
    ```bash
    git clone https://github.com/okzyoping/yolov5-CBAM.git
    ```

2. Navigate to the cloned directory:
    ```bash
    cd yolov5-CBAM
    ```

3. Install required dependencies:
    ```bash
    pip3 install -r requirements.txt --no-cache
    ```

## Training

1. Run the training script with desired parameters (replace 'models/yolov5n-CBAM.yaml' with your desired config file and adjust other parameters as needed):
    ```bash
    python3 train.py --cfg models/yolov5n-CBAM.yaml --epoch 50 --img 640 --data your_custom_dataset --device 0
    ```


Thank you to Roboflow for their support Dataset!

![roboflow](https://github.com/okzyoping/yolov5-CBAM/assets/154805738/62872460-4e1e-4d5f-82f5-af6891af8d7c)

