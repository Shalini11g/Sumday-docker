
# Website Project README

This README provides an overview of the steps taken to set up and initialize the website project and generate Docker image for website.

## Steps Followed:

1. **Create Project Directory:** Created a directory named `website` to store all project-related files usig the command $mkdir website and changed the directory to website using $ cd website.
   
2. **Download Website Assets:** Utilized `wget` to download website assets from the provided URLs.
   
   - Downloaded the main website page from [home.sumday.org](https://home.sumday.org/) and saved it as `index.html`.
   - Attempted to download additional assets but encountered a 404 error.
   
3. **Downloaded Template:** Downloaded a website template from [free-css.com](https://www.free-css.com/assets/files/free-css-templates/download/page295/edgecut.zip) and saved it as `edgecut.zip`.
   
4. **Extract Template:** Extracted the contents of the downloaded template using the `unzip` command as $ unzip unedge.zip.
   
5. **Created Dockerfile:** Created a Dockerfile to containerize the website using vim Dockerfile
   
6. **Built Docker Image:** Built a Docker image named `website` using the Docker build command as docker build -t website.

7. **Check the Docker image:** To check the docker images created use the command $ docker images.
   
8. **Initialized Git Repository:** Initialized a Git repository to manage version control for the project using the command $ git init.
   
9. **Added Files to Git:** Added all project files to the Git repository for version tracking using  $git add.
   
10. **Committed Changes:** Committed the added files to the Git repository using the command  git commit -m with the message "Initial commit" and pushed it to github  git push -u origin master.
