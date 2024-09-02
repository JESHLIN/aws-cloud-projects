                                      Image Labels Generator Using AWS Rekognition

To create an image labeling system using AWS services, we can use AWS Rekognition. AWS rekognition is a powerful service to find objects, people, text, scenes in images and videos using ML. Below are the general steps to set up an image labeling system:
1. Set Up AWS Rekognition:
   Create an S3 Bucket for labelling images. Select an image with multiple objects to showcase the capabilities of labelling. Click on "Add File" to upload the image. Ensure the IAM role has the necessary permissions to access S3 and use Rekognition.
   
![Screenshot 2024-07-02 121928](https://github.com/JESHLIN/aws-cloud-projects/assets/148425817/2186833e-4f75-4c90-b915-15d24df250a9)

![Screenshot 2024-07-02 121951](https://github.com/JESHLIN/aws-cloud-projects/assets/148425817/65d5bcf2-48c6-4c57-a5de-cc7448a1b611)


 2. Importing the required libraries
      
Open your terminal and install the required python library:
"pip install boto3"
"pip install matplotlib"
boto3 is for interacting with AWS Services and matplotlib is used for visualization. Open your preferred IDE and create a file with '.py' extension. You can see the complete code in "label.py".

3. Printing labels
   Open your terminal and change the directory where your python file is present and then run the command "python name_of_the_file.py". Now you can see the output which showcases the 10 detected labels along with their confidence levels. Additionally, a pop-up window will display the image from s3 bucket, highlighting bounding boxes around the identified labels.

    ![Screenshot 2024-07-02 121718](https://github.com/JESHLIN/aws-cloud-projects/assets/148425817/a2c3ec56-4925-462a-98d0-d3b20ef52582)

   ![Screenshot 2024-07-02 121803](https://github.com/JESHLIN/aws-cloud-projects/assets/148425817/22afe8f0-45b0-4aa4-a678-3777365ece76)

