# IDENTIFICATION FORGERY DETECTION

## Context
The Forgery Detection algorithm works on Computer Vision principle. Steps involve uploading an image for detection, change the size, format
and shape according to the original image followed by gray‑scale conversion. Next would be finding the similarity index, compare the images
and check the similarity score to decide tampering/forgery.


## Step to run application:

Step 1:	Clone The Project

Step 2: Open Terminal and change the current path to the one where app.py is found

Step 3: Create a virtual environment: conda create -name <environment name>

Step 4: Activate environment: conda activate <environment name>

Step 5: Install Dependencies: python -m pip install -r requirements.txt

Step 6: Run the application python app.py You will get url copy it and paste in browser.
        
Step 7: sample_data has images on which identification fraud detection can be tested.
        
## Simulation
        
 1) User Interface
        <img width="1321" alt="Screenshot 2021-11-28 at 11 30 21 PM" src="https://user-images.githubusercontent.com/20886645/143780492-e1d14470-31bb-4ff7-be66-0c0b70de1e47.png">
 
2) Fraud is detected with respect to a sample PAN Card identification image

        Original Image 
    
        ![original](https://user-images.githubusercontent.com/20886645/147409754-9236ce6d-9414-4b07-b73f-b275317c9dc9.jpeg)
       
        Fraudulent Image
        
        ![143780611-939d39b5-e891-46eb-af3f-6f3e3ebc5dd5](https://user-images.githubusercontent.com/20886645/147409759-982248af-510f-450a-b9b8-8b1f06f64609.jpeg)

        
## Application is deployed to Heroku Cloud Platform 

URL : https://identification-fraud-detection.herokuapp.com/ 
