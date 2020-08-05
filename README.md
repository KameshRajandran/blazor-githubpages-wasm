# Steps to run the githup pages

* Copy and paste your published folder to seperate folder 
* Add the .gitattributes file in root folder with below comment 

```
* binary
autocrlf=false
```
* Add .nojekyll file to root folder 
* Remove base tag on your index.html file
* Run the below comment 

```
git add --renormalize .
```
