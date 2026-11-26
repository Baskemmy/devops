# My Side Quest: Setting Up the Ubuntu Development Environment

## Why this setup came to mind

While setting up the Ubuntu VM, I realized I could treat it as a separate computer and contributor rather than just another window or app on my Windows PC. So, I decided to use the name `bask-ubuntu` for this environment. This is so that I can practice working on the same GitHub repository from two different systems, and as a plus, run a small simulation of team collaboration.

So, the plan was to take my screenshots and little notes on the ubuntu machine while using the the windows machine to structure the main README.md files and explainer notes based on the screenshots, successfully mimicking team collab.

Well, that's that, let's proceed...

## Step 1: Install Git

In Ubuntu, I opened my Terminal and ran the following commands:

```bash
sudo apt update
sudo apt install git
```

## Step 2: Installing Snap and Visual Studio Code

I used the official [Snapcraft instructions for installing Visual Studio Code on Ubuntu](https://snapcraft.io/install/code/ubuntu) to set up Snap and VS Code.

Once Snap is available, install VS Code with:

```bash
sudo snap install code --classic
```