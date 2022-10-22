# PAN-card-tampering-detection
The purpose of this is project is to detect tampering of PAN card using computer vision. This project will help different organization in detecting whether the id i.e the PAN card provided to them by their employee or customers is original or not

## Scope
This project can be used in different organizations where customers or users need to provide any kind of id in order to get themselves verified. The organization can use this project to find out whether the ID is original or fake. Similarly this can be used for any type of ID like Aadhar card, voter id, etc.

## Run
Step to run application:

* Step 1:	Create the copy of the project.

* Step 2: Open command prompt and change your current path to folder where you can find 'app.py' file.

* Step 3: Create environment by command given below: `conda create -name <environment name>`

* Step 4: Activate environment by command as follows: `conda activate <environment name>`

* Step 5: Use command below to install required dependencies:
`python -m pip install -r requirements.txt`

* Step 6: Run application by command: `python app.py`
You will get url copy it and paste in browser.

* Step 7: You have sample_data folder where you can get images to test.


## Summary

1. Finding out structural similarity of the images helped us in finding the difference or similarity in the shape of the images. Similarly, finding out the threshold and contours based on those threshold for the images converted into grayscale binary also helped us in shape analysis and recognition. 

2. As, our SSIM is ~31.2% we can say that the image user provided is fake or tampered.

3. Finally we visualized the differences and similarities between the images using by displaying the images with contours, difference and threshold.  



