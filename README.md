### Make an image
docker build -t image .

### Run a container
docker run -d -p 7775:3000 --name sharma_diwanshu_assignment_11 image
