---
toc: true
comments: false
layout: post
title: ☆ Activities
description: Tools used during this week
courses: { compsci: {week: 0} }
type: hacks
unit: "1"
---

# <code style="color:#4e804f;">☆ Installations ☆</code>

> ### <code style="color:#4e804f;">☆ VSCode ☆</code>
- Other than installing the app on my device, I had to run a lot of commands on terminal through the VSCode directory. To create the vscode directory on terminal, we ran the following code
```bash
 mkdir vscode
 cd vscode
```
- then we cloned a repository from github, like so
```bash
 git clone https://github.com/alishahussain/student2.git
```
- we also configured git

> ### <code style="color:#4e804f;">☆ Homebrew ☆</code>
- Next, we had to install homebrew, which is a software management software. In this class, we are mainly using it to install other extenstions. 
- I had some errors duirng the homebrew installation process (see "My Journey" tab)

> ### <code style="color:#4e804f;">☆ Other Installations ☆</code>
> 
```bash
echo "=== Upgrade Packages ==="
brew update
brew upgrade
#decompress the file
brew install xz 
# rbenv, Ruby 3.1.4, configure it
echo "=== Install Ruby ==="
brew install rbenv
rbenv install 3.1.4
rbenv global 3.1.4
echo 'if which rbenv > /dev/null; then eval "$(rbenv init - zsh)"; fi' >> ~/.zshrc
rbenv versions 
# Python and Pip through Homebrew
echo "=== Install Python ==="
brew install python
# Jupyter Notebook through Homebrew
echo "=== Install Jupyter Notebook ==="
brew install jupyter
# Gems
export GEM_HOME="$HOME/gems"
export PATH="$HOME/gems/bin:$PATH"
echo 'export GEM_HOME="$HOME/gems"' >> ~/.zshrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.zshrc
gem install jekyll bundler 
```