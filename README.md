We will introduce a smart classroom assistant for educators on our cloud app. The assistant will utilize videos captured in the classroom, conduct facial recognition on the recorded footage, search for identified students in the database, and provide the user with the pertinent academic data for each student.

## Getting Started

- Dockerfile - This file contains the environment setup(ffmpeg and the face_recognition library).
- handler.py - Contains the code to extract frames from videos and perform facial recognition.
- encoding - This file contains the known faces.
- entry.sh - These are the scripts necessary to configure the lambda in the Docker file.
- workload.py - Provided by TA to upload videos.

#### Team Members

1. Suyash Bajpai
2. Amogha Bheemanakone Narappa
3. Harshak Krishnaa Keerthipati

#### Code Structure
. \
├── Dockerfile \
├── Readme.md \
├── encoding \
├── handler.py \
├── mapping \
├── requirements.txt \
├── student_data.json \
└── workload.py 


##### AWS Resources

- AWS Credentials - N/A.

##### S3 Buckets
INPUT_BUCKET = 'input-video-bucket-cloud' \
OUTPUT_BUCKET = 'output-video-bucket-cloud'	 
