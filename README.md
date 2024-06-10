<h1> Image Rekognition and Label Detection </h1>
<h2>Description</h2>
<p>
  This project is a Python script that uses AWS Rekognition to find and name objects in a picture stored in an S3 bucket. It uses Boto3 to connect to AWS, get the image, and find labels with Rekognition. Then, it uses Matplotlib and Pillow to show the image with red boxes around the found objects, adding labels and confidence scores. This project shows how AWS can analyze images and how Python can display the results.
</p>

<h2>Technologies Used</h2>
<ul>
  <li><b> AWS S3: </b> Stores the image to be analyzed.</li>
  <li><b> AWS Rekognition: </b> Detects labels (objects, scenes, and concepts) in the image.</li>
  <li><b> Boto3: </b> AWS SDK for Python, used to interact with AWS services.</li>
  <li><b> Matplotlib: </b> Library for displaying the image and drawing bounding boxes.</li>
  <li><b> Pillow (PIL): </b> Library for image processing in Python.</li>
</ul>
<h2>Procedure</h2>
<ol>
  <li><strong>Open AWS Account</strong></li>
  <li><strong>Create an S3 Bucket:</strong>
    <ul>
      <li>Create a new S3 bucket where we'll store the images to be analyzed.</li>
    </ul>
  </li>
  <li><strong>Set Up IAM User and Permissions:</strong>
    <ul>
      <li>Create an IAM user with permissions to access Amazon Rekognition and S3.</li>
      <li>Generate access keys for the IAM user.</li>
    </ul>
  </li>
  <li><strong>Install Dependencies:</strong>
    <ul>
      <li>Install the necessary Python dependencies using pip.</li>
    </ul>
  </li>
  <li><strong>Write Python Script:</strong>
    <ul>
      <li>Write a Python script that utilizes the boto3 library to interact with AWS services.</li>
      <li>Use the boto3.client('rekognition') method to create a Rekognition client.</li>
      <li>Write functions to detect labels in images using Rekognition and visualize the results using Matplotlib and Pillow.</li>
    </ul>
  </li>
  <li><strong>Authenticate AWS Credentials:</strong>
    <ul>
      <li>Configure AWS credentials in your environment using access keys generated for the IAM user.</li>
    </ul>
  </li>
  <li><strong>Upload Images to S3 Bucket:</strong>
    <ul>
      <li>Upload images to the S3 bucket created earlier.</li>
      <li>Ensure that the images are accessible to the IAM user.</li>
    </ul>
  </li>
  <li><strong>Run the Script:</strong>
    <ul>
      <li>Run the Python script and verify that it can successfully detect labels in the images stored in the S3 bucket.</li>
      <li>Check that the visualization of the detected labels is displayed correctly.</li>
    </ul>
  </li>
</ol>

<h2>Project Outputs</h2>
<div style="display: flex; justify-content: center; align-items: center;">
  <b><p>Configuring AWS</p>
  <img src="https://github.com/khushinim/Rekognition_Label_Detection/blob/master/Output/Configuring%20AWS.jpg">
    <br>
    <br>
  <b><p>Installing Packages</p>
  <img src="https://github.com/khushinim/Rekognition_Label_Detection/blob/master/Output/Installing%20packages.jpg">
    <br>
    <br>
  <b><p>RESULTS</p>
    <img src="https://github.com/khushinim/Rekognition_Label_Detection/blob/master/Output/Example%201.jpg">
    <img src="https://github.com/khushinim/Rekognition_Label_Detection/blob/master/Output/Example%202.jpg">
    <img src="https://github.com/khushinim/Rekognition_Label_Detection/blob/master/Output/Example%203.jpg">
    <img src="https://github.com/khushinim/Rekognition_Label_Detection/blob/master/Output/Example%204.jpg">
</div>
    <br>
    <br>
<div class="center-align">
        <p>Thank you <br>
   ~khushinimawat</p>
</div>

    



