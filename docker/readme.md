## run dockerfile

create the Docker image by running the following command in the directory containing your Dockerfile
```sh
docker build -t theia-minimal .
```

Once the Docker image has been created, you can run a container from it using the following command

```sh
docker run -it -p 3000:3000 theia-minimal
```
Your Theia app container will then be accessible at `http://localhost:3000` in your browser.