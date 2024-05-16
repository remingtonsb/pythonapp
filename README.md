Simple lab to test and deploy an python web server using podman

1- $ git clone https://github.com/remingtonsb/pythonapp.git
2- $ cd pythonapp
3- $ podman build -t pythonapp .
4- $ podman images
5- $ podman run -d -p 8080:8080 pythonapp
6- $ podman ps
7- $ curl localhost:8080
