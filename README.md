# PAN-card-tampering-detection
The purpose of this is project is to detect tampering of PAN card using computer vision. This project will help different organization in detecting whether the id i.e the PAN card provided to them by their employee or customers is original or not

## Scope
This project can be used in different organizations where customers or users need to provide any kind of id in order to get themselves verified. The organization can use this project to find out whether the ID is original or fake. Similarly this can be used for any type of ID like Aadhar card, voter id, etc.

## Run
Step to run application:

* Step 1: Create the copy of the project.

* Step 2: Open command prompt and change your current path to folder where you can find 'app.py' file.

* Step 3: Create environment by command given below: `$ conda create -name <environment name>`

* Step 4: Activate environment by command as follows: `$ conda activate <environment name>`

* Step 5: Use command below to install required dependencies:
`$ python -m pip install -r requirements.txt`

* Step 6: Run application by command: `$ python app.py`
You will get url copy it and paste in browser.

* Step 7: You have sample_data folder where you can get images to test.

## Input 

![tampered](https://user-images.githubusercontent.com/50231750/197356715-46d833b2-3a66-426e-8924-92b5b7bfbc89.jpg)



![original](https://user-images.githubusercontent.com/50231750/197356686-ad4b2e92-5cbb-418c-8b3a-54b8dac37b3f.jpg)

## Output


![interface](https://user-images.githubusercontent.com/50231750/197356802-f790a82b-b717-4978-b6a3-87cf6b556374.png)


### Output-1


![output1_1](https://user-images.githubusercontent.com/50231750/197356832-b48f735a-985f-4f70-a9c0-2bc5ab5df71d.png)


![output1_2](https://user-images.githubusercontent.com/50231750/197356849-02921c48-21f8-4fea-8eee-d36db9a069ba.png)

### Output-2

![output2_1](https://user-images.githubusercontent.com/50231750/197356889-3c354ba9-861a-4454-928b-4b52e5f437f9.png)


![output2_2](https://user-images.githubusercontent.com/50231750/197356917-f715e66c-e794-436b-a479-c26ba47e51d3.png)



## Summary

1. Finding out structural similarity of the images helped us in finding the difference or similarity in the shape of the images. Similarly, finding out the threshold and contours based on those threshold for the images converted into grayscale binary also helped us in shape analysis and recognition. 

2. As, our SSIM is ~31.2% we can say that the image user provided is fake or tampered.

3. Finally we visualized the differences and similarities between the images using by displaying the images with contours, difference and threshold.  



