# WELCOME TO TECH-MATRIX ! 🎉

test

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
Once that's done, come back here and follow these steps ! <br /><br />


   #### 1. Fork this repository
    
   ![image](https://user-images.githubusercontent.com/73497800/132095758-20f82afb-3987-4af8-8935-61282bb91e4c.png)<br/>
     Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.
     
   #### 2. Clone the repository
   
   Now clone the **forked repository** to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon to copy the url of the repo. <br />
   ![image](https://user-images.githubusercontent.com/73497800/132093238-ff7f3a88-fec3-49f1-9929-44122a5223ce.png)

   Open your terminal and run the following git command:<br />
   ```
   git clone <url you just copied>
   ```

   For example: <br/>
   ```
   git clone https://github.com/A-HK/Getting-Started-1.git
   ```
    
   Remember to clone **your forked repository** , not the original one.
    
   #### 3. Create a branch
   
   Change to the repository directory on your computer (if you are not already there):<br />
   ```
   cd Getting-Started
   ```
   
   Now create a branch using the git checkout command: <br />
   ```
   git checkout -b your-new-branch-name
   ```
   
   For example:
   ```
   git checkout -b A-HK-first-contrib
   ```
   
   
   #### 4. Add the necessary details
   
   Woohoo! You're almost there! Open the `contributors-list.md` file and add your name and a little about yourself ! <br />
   ![image](https://user-images.githubusercontent.com/73497800/132095056-7a7d7715-75c6-4118-a1c8-22d98044f8c1.png)

   
   #### 5. Commit your changes

   If you go to the project directory and execute the command `git status` in the terminal, you'll see there are changes. <br />
   Add the changed files to the branch you just created using the `git add` command: <br />
   ```
   git add contributors-list.md
   ```

   Now commit those changes using the git commit command:
   ```
   git commit -m "your message"
   ```
   
   For example:
   ```
   git commit -m "added A-HK details to contributors list"
   ```
   
   #### 6. Push your changes to GitHub
   
   Push your changes using the command `git push`:
   ```
   git push origin <add-your-branch-name>
   ```
   For example:
   ```
   git push origin A-HK-first-contrib
   ```
   
   #### 7. Submit your Pull request for review
   
   ![image](https://user-images.githubusercontent.com/73497800/132095402-2a33defe-072f-45b0-92ea-e2c50f45a2e4.png) <br /><br />
   Go to your forked repository on GitHub and click on the `Compare & pull request` button. <br />

   ![image](https://user-images.githubusercontent.com/73497800/132095416-d35a7fe7-6a55-47b4-8712-435fbc4b6410.png) <br /><br />
   
   Submit your Pull Request, after ensuring that the base repository is `Tech-Matrix/Getting-Started` and head repository is  `<your-username>/Getting-Started` <br/><br />
   
   ![image](https://user-images.githubusercontent.com/73497800/132095867-d9f28b23-f63b-429b-a352-3cf0d20a7214.png)

   
   <br /><br />
   ### ✨Congrats ! You just made a contribution ! ✨
   All you have to do now is sit tight and wait for us to merge your PR :)
