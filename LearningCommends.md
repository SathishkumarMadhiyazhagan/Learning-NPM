# Getting Startrd with npm

##  initials package.json file

npm init - initials package.json file

## adding node Packages

npm install [package name]- node package manager using for install dependancies file 

npm install -D or -sava-dev [package name] using for install dependancies for developement

## Managing globle directory

npm install -g or -globle [package name] using to install package globle in your system don't require to install every time

npx - node package execution install packages temporaily on your system then dose the command remove package in system

spcifice version

npm i [package name]@version number

outdate version

npm outdated

globle outdated

npm outdated -g

## updating a Dependency

update version

npm update [package name]

npm install [package name];

npm install [package name]@latest

npm install [package name]@version number

## Remove dependency

npm uninstall [package name]

npm uninstall [package name] -g

npm uninstall [package name] -save-dev or -D

## Semantic versioning

example npm install express@4.2.1

look at numbers 4.2.1

4 repersent major releases full new version of application
2 - minor releases add new fuction to major releases
1 - patch releases bug fixing

example npm install express@^4.2.1
look at numbers ^4.2.1

caret - ^ - default last major release version 4.x.x minor and patch determined major to last version

example npm install express@~4.2.1
look at numbers ~4.2.1

tild - ~ - default last major release and minor release version 4.2.x patch determined patch to last version

## Introduction package.lock.json

using for controll dependency versions

example express^4.2.3 mapped in package json file we push in git another developer want to use this application that
time express is install 4.5.3 this case problem happend minorly we want to resole this issue we push package.lock.json 
file to git. other developer use this application in there local system that time package.lock.json file used for input to install dependency that we have with respect versions based on that it create output of package.json file.



