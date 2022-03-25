## Back to work with one shell command.
---

### Getting started:
- Add your project to jumpo list 
- Jump to your project with an alias:
```
$ jumpo add code Documents/projects/my_project
$ jumpo my_project
```

That is going to:
- 'cd' into your project directory
- Open choosen editor
- And give some git info:
  
![opened_vscode](images/opened_vscode.png)

### Install:
```
sudo wget -O /usr/bin/jumpo https://raw.githubusercontent.com/slamko/jumpo/master/jumpo && 
sudo chmod +x /usr/bin/jumpo && 
echo "alias jumpo='source jumpo'" >> ~/.bash_aliases
```
*you may want to replace '.bash_aliases' with your preferred config file.
