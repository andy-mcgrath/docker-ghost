Wanted to learn Docker so set a mini project to get a build from uBuntu 15.04 to running Ghost using docker build function.

Step 1: ran uBuntu container and work out what neede to install node.js 10.38, needed unzip and wget or curl for download (went with wget)

Step 2: create Dockerfile to get from base ubuntu 15.04 to install node.js from binary download Step 3: ran container from new image and worked out the basic ghost install Step 4: update Dockerfile to include ghost install and run into build

This is where I currently am with my project

Fucture steps: + Use volumes to allow for central ghost config and database + fork build to include MySQL version of build + add NGINX build (from base uBuntu 15.04 images) to provide reverse proxy front end

Thanks to Amin Meyghani for a Node.js install script (http://stackoverflow.com/users/1265454/amin-meyghani)

Author - Andy McGrath (apextc)
