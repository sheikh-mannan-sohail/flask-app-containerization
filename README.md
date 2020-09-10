# flask-app-containerization
Containarize flask app using docker 

Steps to create an image: 
1. cd to flask-app-containerization
2. docker image build -t python-flask-app-image .
3. Verify image build : docker image ls
4. Run the  container using image 
   docker run -p 5001:3000 -d python-flask-app-image
5. To check if your app is running : 
   Go to browser and type "localhost:5001" - it should display index page
6. To stop container : 
   docker container stop container_id
