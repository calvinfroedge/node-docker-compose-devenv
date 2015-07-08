docker run -p 3000:3000 -d -v $(pwd)/code:/app IMGNAME

The app will be available at:

ip = $(boot2docker ip)
http://$ip:3000/
