# What's gitmumerge?
A simple wrapper of git client. To avoid to crush other modifications, it merges multiple git branches mutually. 

# Requirements
Currently works only on bash. Cui git client is neccesary.

# Configuration
## Install git client 
(debian or ubuntu)

sudo apt-get install git

(redhat or centos)

sudo yum install git


## Install gitmumerge
git clone https://github.com/cocoamaemae/gitmumerge ~/.gitmumerge

echo 'export PATH="$HOME/.gitmumerge/bin:$PATH"' >> ~/.bashrc

source ~/.bashrc

# Usage
git clone "target git repository path"

cd "clone directory path"

gitmumerge -d branch -c branch1 branch2 ....

# More details
(Japanese)
http://qiita.com/cocoa_maemae/items/5908e3b3699c9cea4e8b

(English)
http://cocoamaemae-tec-diary.blogspot.jp/2017/05/gitmerge-to-automatize-merging-multiple.html

