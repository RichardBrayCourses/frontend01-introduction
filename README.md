# Frontend Web Development for Beginners - Step by Step

# Initial Setup

To get started you will need the following software installed:

- Google Chrome
- Node.js
- git (including the git credential manager)
- Visual Studio Code

## Mac Setup

Firstly go to

```
brew.sh
```

and follow the instructions for installing homebrew.

Then use homebrew to install whichever packages you don't already have. Here are the commands.

```
  brew install --cask google-chrome
  brew install node
  brew install git
  brew install --cask git-credential-manager
  brew install --cask visual-studio-code
```

then in a new terminal (to get the correct PATH)

```
  git-credential-manager configure
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
```

## Windows setup

Open a new powershell terminal in admin mode and use winget to install whichever packages you don't already have. Here are the commands.

```
  Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
  winget install Google.Chrome
  winget install OpenJS.NodeJS
  winget install Git.Git
  winget install Microsoft.VisualStudioCode
  winget install Amazon.AWSCLI

```

then in a new terminal (to get the correct PATH)

```
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
```

# Clone this repo

- Open the course repo in GitHub
- Click on the green "Code" button
- copy the HHTPS address of the repo
- Open Visual Studio Code
- Select View->Command Palette
- Choose git clone
- enter the HHTPS address you copied above
- select a folder where the repo is to be cloned on your hard drive

# Build the Final Application

- Open the repo folder in Visual Studio Code
- Open a terminal window

Enter these commands

```
npm install
npm run dev
```

- Open the vite link in a browers (should be something like http://localhost:5173)
