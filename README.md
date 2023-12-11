# gitAndGitHubEssentials
Outlining the basics of Git and GitHub 
## What is Git and GitHub
Git is a software tool. It is a distributed version control system that is used by Developers to track changes made to files and directories. Git is designed to be used through a Command Line Interface, CLI, that is, typing commands into a terminal or command prompt. However, it can also be used with Graphical User Interfaces, GUIs.  
GitHub is a web-based platform that is used to host software developments and version control using Git. It is an effective collaboration platform for Developers to:  
- manage different versions of their codes
- track changes
- work together on projects
  
It is also useful for the followings:
- Making Pull requests. That is, suggesting modifications and additions to codes
- Streamlining development processes with GitHub Actions. This makes it easy for Users to automate workflows for building, testing, and deploying projects.
- Creating and maintaining project documentations with wikis and README files

To download Git for your local use click [here](https://git-scm.com/downloads) and to create your GitHub account use this [link](https://github.com/)  

## How to Configure Git   
After downloading Git to your machine, type **git --version** to confirm the version of Git downloaded as seen below  

![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/ca58fd25-6337-4a8f-a36b-4dc9b30b0ddd)
 
Next, configure the working environment for your use. This is very important because all actions performed on the Git has to be associated with an identity. Therefore, you have to configure it with User name and email. This is illustrated below  

![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/ef8c8b4a-24df-4b97-ae12-ffde1d10552f)  

To confirm that you have configured the environment with your Username and email, type **git config --list**  

## Configuring Git Working environment  
1. Create a directory. Use the command **mkdir** and the directory name to do this. For example, to create a directory named Website, type *mkdir Website* into your terminal

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/dde07576-d6c2-4817-afa1-1d1f3e228ae2)

2. Use the command **ls** to confirm that the directory has been created. This command will list all the directories in the environment

3. Navigate into the directory by using the command **cd**. For the directory created in Step 1 above, type *cd Website*

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/cebb654e-29e8-40ba-a2c5-5c5cf75f6baa)

4. Initialise the directory with the command **git init**

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/b0fb15bb-6cf5-4dc3-956a-264dc5447461)

5. Create the file that you want to use with the command **touch**. To create a text file *index.html*, type *touch index.html* and use ls to confirm that it ahs been created

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/ff9effc3-5f3f-4167-91c0-0d0d62ba0f35)

6. To edit the index.html file, use **vim** as shown in the image below

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/1566f690-557e-4b89-a432-856a687a5de7)

   This will take you to the Editor's window and you can input your text as desired.
   
   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/b9eddfce-1455-480c-b840-722ca513537b)

7. To save the text in the file and quit the Editor, press Esc on your keyboard and them type **:wq** and press the Return button on your keyboard. This will take you back to the Terminal window

8. Next, type **git status** in the Terminal to check the status of your actions so far

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/7913743f-67e9-40d0-b068-18b17454a2e0)

   The output showed that there are files created but are not tracked. To track the changes made in the files, they have to be added to the Staging area.

9. To add index.html file to the staging area, use **git add index.html .**

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/927d3340-54d8-406f-819f-3606177e4337)
 
10. Now, use **git status** again to confirm that the file changes is being tracked

    ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/a80d2eab-1a31-484b-a34a-bf8ba52b5b74)

## Working with GitHub  
1. Log in to your GitHub account and create a new repository. You can follow this [guide](https://github.com/Yemmy-Oye/creatingRepoInGitHub) to create one. For this exercise I will create a repository named *teachingGit*

2. Click on *Code* on the repo and select *HTTPS*. Then copy the URL under HTTPS.

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/2f518bcc-9b5a-4175-961c-0dec717c1141)

3. Next, go to your Git terminal to clone the repository. Use the command **git remote add origin** together with the repo URL copied in step 2 above

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/78038e8e-144a-466e-9bcf-76b504ad7c6a)
   
4. To take a snapshot of the current status of the repo and attach a commit message to it, use **git commit -m**. My commit message will be *my first commit*

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/9a36e6d5-9ea0-4ffd-a7c2-8b99ecae195e)

5. Push the commit to GitHub by typing **git push origin master** in the terminal.

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/4417d907-10da-48f6-9ef1-da5e683b8f13)

   The output shown in the image above indicated that the commit has been pushed to Github. Lets proceed to GitHub to confirm.

   ![image](https://github.com/Yemmy-Oye/gitAndGitHubEssentials/assets/129787413/8979446a-6c2b-4ddb-b75a-3e712f96c0e3)

I hope you find this repo helpful



    




   



   



   

   


   
   

    

   







