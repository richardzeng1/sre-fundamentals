# Nginx 
[Nginx Official Documentation](https://docs.nginx.com/)

Nginx is as lightweight web server which can function as a reverse proxy, ingress controller, service mesh and more. It is one of the most common tools used in production environments so it is important to learn what problems the tool is trying to solve and how it implements the solution.

## Table of Contents
1. Introduction
2. Installation on Linux
3. Basic Walkthrough and Important Concepts

## 1. Introduction
Nginx is as lightweight web server which can function as a reverse proxy, ingress controller, service mesh and more. It is one of the most common tools used in production environments so it is important to learn what problems the tool is trying to solve and how it implements the solution. If you take a look at the [Nginx admin documentation](https://docs.nginx.com/nginx/admin-guide/), you can see some common use cases.

## 2. Basic Concepts
On Linux, Nginx is a Systemd service. You can check the health and status of Nginx with the standard `systemctl` commands. There is one master process and many worker processes. The master reads the configuration file and attempts to implement the configuration. The number of worker nodes is also configured in that file. To interact with Nginx, we can use `systemctl` or use `nginx` and send [signals](https://nginx.org/en/docs/control.html). 
