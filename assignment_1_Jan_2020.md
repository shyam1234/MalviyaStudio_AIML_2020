### Only python version of the API needs to be developed here

### Data is available in data folder
https://drive.google.com/file/d/1_kx4J0ZC5Q8Ka4GQtcWGDNGo5tgY_-zs/view?usp=sharing
https://drive.google.com/file/d/1AK7ptCarNFh-nfqSpuhHE_HDHuYx4zBe/view?usp=sharing

- Problem Details
  - Personality detection and Recognition
    - There are 15 celebrities' images in "vision_hackathon_drive.zip" in respective folders.
    - Build a personality detection and recognition model to detect a multi-face/multi-personality image (single image multiple face/personality) such as in validation set "vision_hackathon_drive_val.zip"
    - It is possible that some images might not contain any face/person.. 
    
  - Run the model on a live video URL for real-time recognition and detection.
  
- Write the following API
   - API for static images
      - def detect_and_draw_faces(image)
   - For Live Youtube 
      - Capture Video frame by frame call the above API
    
    

- Dataset 
  - Train set - 15 celebrities, Aprox 100 each
  - Test set - 8 images (multi-face)

- Evaluation
  - Manual evaluation on spot. If you come up with a metric, that's a bonus.
  
  Once, your assignment complete. Commit the link in git.
