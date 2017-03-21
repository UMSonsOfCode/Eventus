# Eventus

# Eventus Important Links and Notes

Laravel Server Link: http://eventus.us-west-2.elasticbeanstalk.com/ (Laravel Project Docs)

Api Link: http://eventus.us-west-2.elasticbeanstalk.com/api

Eventus Web Project Link: http://salty-citadel-11826.herokuapp.com

# Eventus Project Managing

Kanban Board: https://github.com/kennyhong/Eventus/projects

Google Drive: https://drive.google.com/drive/folders/0B4BZ-hWf1OVHcGhiUEdtVGZxRmM?usp=sharing

API-Wiki: https://github.com/kennyhong/Eventus-Server/wiki

# How the Backend Works

Each iteration of the Eventus Server will deployed using `eb deploy` with Amazon's Elastic Beanstalk. This makes deploying the app easy and the api is functional within minutes.

# Code Custodians

Server: Paul/Jeff

iOS: Kieran

Android: Eric/Bailey

Web: Mitchell/Marvin

DevOps: Kenny

# Submodules

This is the main project repository. To access the relevant submodules and their relevant documentation, you can find them here:

Server: https://github.com/kennyhong/Eventus-Server.git  
Server Wiki: https://github.com/kennyhong/Eventus-Server/wiki (API, JSON spec, etc.)  

Android: https://github.com/kennyhong/Eventus-Android.git

iOS: https://github.com/kennyhong/Eventus-iOS.git

Web: https://github.com/kennyhong/Eventus-Web.git

    NOTE: `git pull` will not update the submodule, only it's pointer! Please use `git submodule update --init` after a pull to update the submodule code inside the main repository folder
    
If you want to make it easy, just create a shortcut `git config --global alias.update '!git pull && git submodule update --init --recursive'` and this will pull AND update when you use `git update`
afterwards is as simple as doing `git submodule foreach git pull` to pull each of the code of each of the submodules, since they are their own repositories.

# Sources (Please read if you have a moment):

https://gist.github.com/gitaarik/8735255

http://stackoverflow.com/questions/5828324/update-git-submodule-to-latest-commit-on-origin/5828396#5828396
