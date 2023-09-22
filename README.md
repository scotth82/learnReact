# learnReact

## Setup
### :point_right: NVM - Node Version Manager
- NVM needed to install Node.js and allows you to switch among different Node versions as needed by project
- ❓what are some version issues for Node.js since we need this NVM
- https://github.com/nvm-sh/nvm
- version: 0.39.5
- install and setup:
  ```
  brew install nvm
  ```
  You should create NVM's working directory if it doesn't exist:
  ```
  mkdir ~/.nvm
  ```
  Add the following to your shell profile e.g. ~/.profile or ~/.zshrc:
  ```
  export NVM_DIR="$HOME/.nvm"
  [ -s "/usr/local/opt/nvm/nvm.sh" ] && \. "/usr/local/opt/nvm/nvm.sh"  # This loads nvm
  [ -s "/usr/local/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/usr/local/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion
  ```
- check version:
  ```
  nvm -v
  ```

### :point_right: Node.js
- :question: what is Node.js? what does it do? some client side react exeuction thing?
- https://nodejs.org/en
- version: 20.7.0
- install:
  ```
  brew install node
  ```
- check version
  ```
  node -v
  ```

