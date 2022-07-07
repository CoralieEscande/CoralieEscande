# Versioning Environnement


##  git version 
2.37.0.windows.1


## Current configuration
### How to configure :
$ git config --global user.name "Coralie ESCANDE"  
$ git config --global user.email coralie.escande@gmail.com  
$ git config --global color.diff auto  
$ git config --global color.status auto  
$ git config --global color.branch auto  
$ git config --global core.editor "Visual Studio Code"  
$ git config --global merge.tool "Visual Studio Code"  
$ git config --global alias.lola "log --graph --decorate --pretty=oneline --abbrev-commit --all"  
$ git branch -M main  


### Verify the configuration : $ git config --list
diff.astextplain.textconv=astextplain  
filter.lfs.clean=git-lfs clean -- %f  
filter.lfs.smudge=git-lfs smudge -- %f  
filter.lfs.process=git-lfs filter-process  
filter.lfs.required=true  
http.sslbackend=openssl  
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt  
core.autocrlf=true  
core.fscache=true  
core.symlinks=false  
pull.rebase=false  
credential.helper=manager-core  
credential.https://dev.azure.com.usehttppath=true  
init.defaultbranch=master  
user.name=Coralie ESCANDE  
user.email=coralie.escande@gmail.com  
color.diff=auto  
color.status=auto  
color.branch=auto  
core.editor=Visual Studio Code  
merge.tool=Visual Studio Code  


## How to import the distant repository to your local directory
$ git remote add depot_distant https://github.com/CoralieEscande/Excercices.git  
$ git clone https://github.com/CoralieEscande/Excercices.git  


  
