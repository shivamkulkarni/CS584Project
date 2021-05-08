# CS584 Project
Illinois Institute of Technology
Student: Shivam Kulkarni(skulkarni17@hawk.iit.edu)

How to download data
--
##### `$ wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1ZVCHVgGh3KZc8SwL9QuVtjEnSC2ddraH' -O stage1_train.zip`
##### `$ wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1tPcxWKCXaV5SJJn9GsGQGKc3mFCGBSbO' -O stage1_test.zip`
##### `$ mkdir stage1_train stage1_test`
##### `$ unzip stage1_train.zip -d stage1_train/`
##### `$ unzip stage1_test.zip -d stage1_test/ `

Data is stored in google drive and data expected to be in stage1_train folder


U-Net Architecture
--
![image](https://user-images.githubusercontent.com/22586461/117525202-bad60a00-af86-11eb-8e0e-b186f24d8dc4.png)

Results
--
Dice coefficient on training data   : 0.86 <br/>
Dice coefficient on validation data : 0.86

