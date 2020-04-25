# docker-build
Docker build for local environment setup at Taylor University. Please read through Section 1 before setting up your environment. We

----
## Section 1

Instructions are using the following tools:
- [Microsoft VS Code](https://code.visualstudio.com/download)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)

For Microsoft VS Code, it is suggested to use the following extensions:
- [Docker by Microsoft](https://marketplace.visualstudio.com/items?itemName=formulahendry.docker-extension-pack)
- [Live Share by Microsoft](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack) *(not required)*

----
## Section 2: Build dotCMS Environment
*More detailed information, please see [DotCMS Documentation](https://dotcms.com/docs/latest/getting-started-with-dotcms-in-docker-containers) about multiple container builds*

1. **Get** latest dotCMS image for DockerHub
```
docker-compose pull
```
2. **Run** the build
```
docker-compose up
```
3. **Access** your local site at http://localhost:8080/.
4. **Check** that everything is correct so far. You should see two containers running(application and database)
```
docker ps
```

----
## Section 3: Import TU the database to database container