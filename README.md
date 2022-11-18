# cbwa_ca2

Name: Rosana Cardoso Batista Torres ID: 2022000 - Graduation Course at CCT College Dublin

## Task: Cloud-based Web Applications:

Build Docker Image that contains the Ionic application built for Mobile Development with a server and that is ready to be distributed to any cloud provider that supports Docker containers.

## Start:

First I created the repository on Github and downloaded the repository to be able to proceed with it in VSCode.

## Usage:

    -> Build the image

```sh
docker build -t cbwa_ca2 .
```

    -> Run the image on port 8080:

```sh
docker run -it --rm -p 8080:80 cbwa_ca2
```
Browse to `http://localhost:8080`.

## 5 Top Cloud Providers in 2022

    1. Amazon AWS Cloud
    2. Microsoft Azure
    3. Google Cloud Platform (GCP)
    4. Alibaba Cloud
    5. Salesforce

## Amazon AWS Cloud

Amazon Lightsail offers easy-to-use Virtual Private Server (VPS) instances, containers, storage, databases, and more at an affordable monthly price.

** Run simple web apps: Use pre-configured development stacks like LAMP, Nginx, MEAN and Node.js. to get online quickly and easily.

** Create custom websites: Create and customize your blog, e-commerce or personal website in just a few clicks with pre-configured applications like WordPress, Magento, Prestashop and Joomla.

** Create apps for small businesses: Launch line-of-business software such as file storage and sharing, backups, finance and accounting software, and more.
 
** Spin test environments: Easily create and delete development sandboxes and test environments where you can try out new ideas risk-free.

## References

### Node version check
** https://hub.docker.com/_/node
### Build Node image
** https://docs.docker.com/language/nodejs/build-images/
** https://github.com/ppdeassis/docker-node-nginx-alpine
### Build Docker image from github
** https://stackoverflow.com/questions/50546672/how-to-pull-docker-image-from-github-and-build-image-in-ec2
### Dockerfile (COPY, USER, EXPOSE, WORKDIR)
** https://docs.docker.com/engine/reference/builder/
### Angular in Docker with Nginx, supporting configurations
** https://github.com/tiangolo/blog-posts/tree/master/angular-in-docker
