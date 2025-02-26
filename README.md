# Instagram tech stack buildout with Flask and Docker

## Overview

This repo follows the [TestDriven.io](https://testdriven.io/blog/dockerizing-flask-with-postgres-gunicorn-and-nginx/) tutorial to set up a Flask-based web service using Docker. The build out is an approximation of Instagram's tech stack. I use Docker, PostGres, Gunicorn and Nginx to enable this web service. This web service allows you to host static files, as well as upload media and view it on the web service.

**Example file upload**

In the screenshots below, you can see me uploading a gif file to the web service.

Firstly, the upload functionality on the web service is accessed. In my configuration, this is at the address `http://localhost:5100/`
![Webservice is accessed on local host](sc1.png)

Secondly, a gif is uploaded
![Gif is uploaded to web service](sc2.png)

Thirdly, the gif can be previewed on a newly established page!
![Gif is viewed on webservice](sc3.png)


## Build instructions
