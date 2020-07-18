![](../../common/images/customer.logo2.png)
# Microservices on ATP #

## Part 1 - Setting up your Visual Builder Studio Project ##

## Introduction ##

In this lab, you’ll learn how to set up a new Visual Builder Studio project, based on a Github repository, and start modifying and automating the CI/CD steps for your environment.

You will work with Visual Builder Studio and learn about some of its most important features.  

Let’s get started! 

## Steps

### Step 1: Create a project environment for your team

In this section, you’ll provision a complete development platform for your team by leveraging the Visual Builder Studio web interface.

- Access your Visual Builder Studio Instance by following the link provided to you in the access document

  

We pre-created a Visual Builder Studio project environment for you to use.  In order to access this environment, perform following steps : 

- On the Welcome page, click **All** to see all projects in the environment.

  ![](images/150/image001-3c.png)

- Locate the project you have been assigned to according to the **Number** your instructor will have assigned to you : for example if you are **participant 09**, and your event is called **my_event**, please use project **09_myevent**.

- Now click on the hamburger icon on the right of your project, and select the option **Assign me as Owner**.

![](images/150/assign.png)



- You can now access your project and are ready to start the exercise.



![](images/150/image006-1.png)

Let’s take a look at this page (you may need to scroll to see the whole thing): 
- On the left side is an activity feed. 
- Tabs on the right side show you where the Git source code and Maven repositories are located.
- Also on the right you can see project statistics, as well as the UI where you can manage team members.  Let’s take a look at that UI now. 




### Step 2:  Fetch and review code from the Git repository

- With the **Project Home** selected on the left menu, look to the right and select **Repositories**, then click **+ Create** button.

  ![](images/150/image006-2.png)

- In the New Repository dialog, enter these details: 
  - Type **ATPDocker** in the **Name** field.  In case you are sharing a repository with other participants, add your initials at the end of the name, like for example **ATPDocker_JLE**

  - Type **Microservices and ATP** in the **Description** field

  - Choose **Import Existing Repository** under **Initial content**

  - Enter https://github.com/CloudTestDrive/ATPDocker.git in the text box: 

    ![](images/150/image010-3.png)

- Click **Create**.

  You should now be on the Code tab, which shows that you have a new git repository, called NodeJSDocker.git.  This new repository contains imported code from the GitHub repository you specified.

  ![](images/150/image011-3.png)



You are now ready to start configuring your CI/CD flows in this project!

- create the necessary database objects
- build your application Docker Container
- deploy the container to a Kubernetes cluster



---

You finished all the steps of Part 1.   Use the menu to navigate to the next chapter.





