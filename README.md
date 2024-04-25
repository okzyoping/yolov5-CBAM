# yolov5-CBAM
test on ubuntu 20.04


Ubuntu 20.04

# create environment
1. sudo apt update
2. sudo apt upgrade
3. sudo apt install virtualenv
4. virtualenv -p /usr/bin/python3 change_with_your_name_environment
   
# aktivate environment
1. source your_name_environtment/bin/activate

# clone my repository to run the code 
1. git clone https://github.com/okzyoping/yolov5-CBAM.git
2. cd yolov5-CBAM
3. pip3 install -r requirements.txt

# Train code 
1. python3 train.py --cfg models/yolov5n-CBAM.yaml --epoch 50  --img 640  
