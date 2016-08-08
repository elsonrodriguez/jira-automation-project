# Automation via Jira
Most common Jira workflows and screens do not lend themselves to the types of simple inputs and outputs that define most automation. This guide will help you create a Jira project that is easily parsable by humans and computers!

In this example, we will be creating a Jira project that can interact with a container image deployer.

## Create a Project

Create a new project From the administration page

![](create-project-1.png)

Select "Task Management" as the project type and hit next

![](create-project-2.png)
Click "Select"

![](create-project-3.png)
Enter your project name, in this example we are creating a Deployment workflow

![](create-project-4.png)
Click submit

## Create your Issue Type

Go to the Issues Administration page

Click on "Add Issue Type"

Enter the name of the task type, in this case this is a Deployment

Now we must create an Issue type scheme to associate our project with the Deployment task. Create a new Issue Type Scheme called "Automaton". Add "Deployment" as the Issue Type, and "Deployment" as the Default Issue Type"

Associate the scheme with your project:



## Create your Fields

We must make a small detour here to make setting fields up easier. We're going to create a Screen for our project.

Next, create a single line text field:

And we name it "Container Image"

Associate the field with the screen for our project:

Repeat this procedure for any other fields

## Configure your Screen



## Create your Workflow


