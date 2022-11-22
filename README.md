# static_web_page
This is a assignment project

Here we are using Github to host our websites. 
Technology used - HTML
we need a terminal git bash or any terminal where git needs to be installed. Here I was using AWS EC2 Linux machine(free tier) and installed git  in that using below command
yum install git -y 
after installing git and generating ssh keys(ssh-keygen) we need to add ssh pub keys to our github settings.
we will be able to git clone the repo inside the machine.
once the repo is cloned go inside the folder and add one more folder by using nano editor
nano index.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GFG</title>
</head>
<body>
    <h1>Hello World this is my first web page.</h1>
</body>
</html>

to save and exit nano editor you need to type-  ctrl+O (saves the file) ctrl+X(exit the file) enter.

Run few git commands
git status
git add .
git commit "message"
git push origin <branch name>
 
once the change is pushed to the repo we can see one more folder index.html in our repo.
Now we are good with the webpage

  
Now just follow these steps.

Go to repo setting and scroll down to Github pages
Click on the dropdown currently showing none and select your branch in our case it is main/master.
Click on save, you can see a url on the top of it in the format of https://<username>.github.io/<repo name>. This is url of your hosted webpage.


Our requirement is to make simple webpage with authentication mechanism
