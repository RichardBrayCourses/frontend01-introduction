# Frontend Web Development for Beginners - Step by Step

# Initial Mac Setup

To get started you will need the following software installed:

- Google Chrome
- Node.js
- git (including the git credential manager)
- Visual Studio Code

## Step 1 - install homebrew

Firstly go to

```
brew.sh
```

and follow the instructions for installing homebrew.

## Step 2 - update your shell startup file

Once homebrew is installed you **must update your shell startup file**

Enter this command into a terminal to find out which shell you are using

```
echo $SHELL
```

If it replies "/bin/zsh" you are using zsh ... so enter this command into your terminal to update the startup file

```
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
```

If it replies "/bin/bash" you are using the bash shell ... so enter this command into your terminal to update the startup file

```
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.bash_profile
```

## Step 3 - install software for course

Then use homebrew to install whichever packages you don't already have. Here are the commands.

````

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

# Frontend Web Development for Beginners - Step by Step

# Initial Windows Setup

To get started you will need the following software installed:

- Google Chrome
- Node.js
- git (including the git credential manager)
- Visual Studio Code

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

- Open the course repo on the GitHub website
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
```
````
