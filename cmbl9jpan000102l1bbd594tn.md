---
title: "Day 1 - Web Dev to AI Engineer : Hello AI World"
datePublished: Fri Jun 06 2025 20:34:01 GMT+0000 (Coordinated Universal Time)
cuid: cmbl9jpan000102l1bbd594tn
slug: day-1-web-dev-to-ai-engineer-hello-ai-world
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1749236347764/27d2b791-0f43-4a32-bc5f-f270f6ad15bc.png
tags: 100daysofcode, build-in-public, ai-engineer, ai-journey

---

PHP/CodeIgniter to Artificial Intelligence - join me on my journey to become an AI Engineer.

My journey will be in 5 phases (The Roadmap).

* **Phase 1 - AI Engineer Foundation**  
    In this phase the goal is to learn Python fluently and get into the AI Engineering mindset.
    
* **Phase 2 - Machine Learning Kickstart**  
    In this phase the goal is to learn the core ML concepts and build some learning projects.
    
* **Phase 3 - Deep Learning & NLP Basics**  
    In this phase the goal is to learn to build AI-powered apps chat-bots, translators and more.
    
* **Phase 4 - Data Engineering + Real World AI Apps**  
    In this phase the goal is to learn how AI engineers work in production.
    
* **Phase 5 - Capstone Projects**  
    In this the goal is to build professional real world app and ship it out in the world.
    

## Phase 1 : Day -1

### Focus: Environment Setup and First Steps in Python

As an experienced web developer, transitioning into AI feels exciting but sometimes a bit scary.

Today, I started Phase 1 of my Roadmap to becoming an AI Engineer.

## What I Did

### Installed My AI Dev Stack

1. Python 3.12.2  
    I downloaded the Python from its [website](https://www.python.org/downloads/windows/) and installed it on my laptop.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749216522528/7a7acf24-1eec-421d-b625-0e5ffee62386.png align="center")
    
2. Visual Studio Code extensions - **Python** & **Jupyter**  
    I have been using VS Code for several years now. You can download it for free from its [website](https://code.visualstudio.com/) and install it.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749217917143/b8e544ae-c6d1-422e-b50f-c382e73161a5.png align="center")
    
    After installing VS Code, open the application. Then go to **View** &gt; **Extensions** option.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749218348123/4899509d-ade4-45ae-ab1d-d5f83a40dd25.png align="center")
    
    In the Extensions sidebar search box, lets type **Python.** When the extension appears, click **Install** button. Similarly we can install **Jupyter** extension.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749219069092/a794cf78-c67d-40c8-bb22-5f773eadfb9b.png align="center")
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749219475400/d706b6b8-84b4-46d4-a96f-2aa5a4638912.png align="center")
    
    Note: When you first run a Jupyter notebook, VS Code will ask for your permission to install the **ipykernel** package before running it.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749238555480/bb8c95c5-5eb6-4762-b5c0-ef0294afb6ea.png align="center")
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749238586348/587d8627-7b07-4285-b286-204e96217d31.png align="center")
    
3. Virtual Environment  
    It is a Python environment, that is self-contained directory which includes.
    
    * A Python interpreter
        
    * Set of installed package/libraries
        
    * Their versions of packages/libraries can differ for different projects
        
    * It is a Python environment, that is self-contained directory which includes.
        
        Create using **venv** (recommended)  
        **Step 1: Check if Python is installed**  
        Run the following command to verify that Python is installed:  
        ***python --version***
        
        ***python3 --version*** *(for mac)*
        

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749225393102/9829b6d3-2b7b-4784-8d64-5345d45c97c8.png align="center")

We need to make sure the Python version is 3.6 or higher.

**Step 2: Create a Virtual Environment**  
Run the following command in your project folder:  
***python -m venv &lt;env name&gt;***

***python3 -m venv &lt;env name&gt;*** *(for mac)*

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749227093062/ea7de4b0-41f8-4187-aca0-478b7506fe01.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749227177554/24f12f25-0a4f-45d9-a880-9f831127c090.png align="center")

In the screenshot above, you can see a folder in the left panel with the same name as your virtual environment.

**Step 3: Activate the Virtual Environment**  
In Windows CMD or Powershell  
***&lt;env name&gt;\\Scripts\\activate***  
In Mac/Linux  
***source &lt;env name&gt;/bin/activate***

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749228992506/ecdd5054-98d8-4c9d-9279-17de2478eb52.png align="center")

When the environment is activated, you will see the environment name in brackets (refer to the screenshot above).

**Step 4: Install Required Packages**  
Once the environment is activated, you can install dependencies using the following command.  
***pip install package\_name***  
Example:  
***pip install panda numpy***

**Step 5: List Installed Packages**  
To view all the installed packages in the virtual environment  
***pip list***

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749234670445/ed69ebe1-2690-4b0d-93a7-739130c762a2.png align="center")

**Step 6: Deactivate the Environment**  
To exit the virtual environment when done  
***deactivate***

---

## My First Notebook

In VS Code, go to **File** &gt; **New File** and create a new file with the **.ipynb** extension.

```python
print("Hello World")
```

After typing the code, press **Ctrl** + **Enter** to display the result.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1749239971209/46afe2c2-f35e-4f38-87bf-425d2d2a8dfb.png align="center")

Seeing the message felt more exciting than **Hello World** ever did. This is the first line of code in a journey.

## Reflection

Setting up may not be glamorous, but it’s the runway to liftoff. Every great AI project starts with the right tools in place.

## What’s Next

* Python Core - Basic syntax, Data types, Operators, Conditional Statements, Loops