# gitmerge
Simple wrapper of git clinent. It makes merging git branches easier.

# Requirements
Currently works on only bash.

# Install
git clone git@github.com:cocoamaemae/gitmerge.git ~/.gitmerge

echo 'export PATH="$HOME/.gitmerge/bin:$PATH"' >> ~/.bash_profile

source ~/.bash_profile

# Usage
gitmerge -d branch -c branch1 branch2 ....

# Liscense
MIT
