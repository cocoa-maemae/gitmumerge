# gitmerge
Simple wrapper of git clinent. It makes merging git branches easier.

# Requirements
Currently works only on bash.

# Install
git clone https://github.com/cocoamaemae/gitmerge ~/.gitmerge

echo 'export PATH="$HOME/.gitmerge/bin:$PATH"' >> ~/.bash_profile

source ~/.bash_profile

# Usage
gitmerge -d branch -c branch1 branch2 ....

# Liscense
MIT
