# ...nvm


(Install nvm)[https://github.com/nvm-sh/nvm]

Commands. COmand git and comand help
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion

```
Use
```
# Install versions
nvm install 16.13.0

# List versions
nvm list

# Use on version
nvm use 14.18.1

# Use defatul on start system
nvm use 14 --default

```

