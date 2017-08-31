# hellonode

docker hello world in node

* First, build the image:

    docker build -t hellonode .

* Then create the container

    docker create -p 3000:3000 --name="wonderful_hellonode" hellonode

* Launch it

    docker start wonderful_hellonode

* In a browser, go there

    http://<your_ip>:3000

You should see the string "Hello World"


* Then stop your container

    docker stop wonderful_hellonode


