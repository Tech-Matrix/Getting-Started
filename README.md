# WELCOME TO TECH-MATRIX ! 🎉

We're so glad you found yourselves here!

The current iteration of Tech-Matrix has two subdivisions :
* [Project Workbench]()
* [Open Source September](https://github.com/Tech-Matrix/Getting-Started/blob/main/README.md#-open-source-september)

### 📌 Open Source September

A 4-week odyssey of learning and hands-on contribution for beginners to start their open-source journey !

What's in store:

![Open_Source_September_Schedule](https://user-images.githubusercontent.com/73497800/132090890-e7ec7626-898c-429a-b581-0e9a580dbfbf.png)



### Making Your First Contribution

**First off, if you don't have git set up on your machine, [install it here](https://docs.github.com/en/get-started/quickstart/set-up-git).** <br/>
Once that's done, come back here and follow these steps !


   #### 1. Fork this repository
    
   ![image](https://user-images.githubusercontent.com/73497800/132091266-43eee21c-5831-40be-b580-c715037cf2da.png)<br/>
     Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.
     
   #### 2. Clone the repository
   
   Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon to copy the url of the repo. <br />
   ![image](https://user-images.githubusercontent.com/73497800/132091517-75610254-b897-44d5-93b6-fb0037314fc2.png)

   Open your terminal and run the following git command:<br />
   `git clone <url you just copied>`

   For example: <br/>
    `git clone https://github.com/A-HK/Getting-Started-1.git`
    
   Remember to clone **your forked repository** , not the original one.
    
   #### 3. Create a branch
   
   Change to the repository directory on your computer (if you are not already there):<br />
   `cd Getting-Started` <br />
   
   Now create a branch using the git checkout command: <br />
   `
   git checkout -b your-new-branch-name
   ` <br />
   
   For example:
   `git checkout -b A-HK-first-contrib`
   
   
   #### 4. Add the necessary details
   
   Congrats! You're almost there! Open the `contributors-list.md` file and add your name and a little about yourself ! <br />

   If you go to the project directory and execute the command `git status`, you'll see there are changes. <br />
   Add the changed files to the branch you just created using the `git add` command: <br />
   `git add contributors.md`

   Now commit those changes using the git commit command:
   `git commit -m "your-message"`
   
   For example:
   `git commit -m "added A-HK details to contributors list"`
   


