# gitmerge
Simple wrapper of git clinent. It makes merging git branches easier.

# Requirements
Currently works only on bash. Cui git client is neccesary.

### git client install

(debian)

sudo apt-get install git

(redhat)

sudo yum install git


# gitmerge Install
git clone https://github.com/cocoamaemae/gitmerge ~/.gitmerge

echo 'export PATH="$HOME/.gitmerge/bin:$PATH"' >> ~/.bashrc

source ~/.bashrc

# Usage
git clone "target git repository path"

cd "clone directory path"


gitmerge -d branch -c branch1 branch2 ....

### More details
(Japanese)
http://qiita.com/cocoa_maemae/items/5908e3b3699c9cea4e8b

(English)
http://cocoamaemae-tec-diary.blogspot.jp/2017/05/gitmerge-to-automatize-merging-multiple.html

# Liscense
MIT
