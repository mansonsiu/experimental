# Setup

### Firebase - codelab - FriendlyChat
https://codelabs.developers.google.com/codelabs/firebase-web/#0
#

### Tools
- ATOM
- NPM
#

### Problem 1
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun

It means that you need to install XCode command line, open a Terminal and run this command:

$ xcode-select --install
#

### 2. Get the sample code

Clone the GitHub repository from the command line:

$ git clone https://github.com/firebase/friendlychat-web
#

### 3. Install NPM
Problem - Permission error
To install or update nvm, you can use the install script using cURL:

curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash

The script clones the nvm repository to ~/.nvm and adds the source line to your profile (~/.bash_profile, ~/.zshrc, ~/.profile, or ~/.bashrc).

export NVM_DIR="$HOME/.nvm"

[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

$ sudo chown R $USER /usr/local

$ ls -l /usr/local

$ npm -v

$ npm i npm@latest -g

$ npm -g install firebase-tools


To verify that the CLI has been installed correctly open a console and run:

$ firebase --version

Make sure the version of the Firebase CLI is above 3.3.0

Authorize the Firebase CLI by running:

$ firebase login

