# mx-entypo-icons
Entypo Icon Font converted for use in Mendix
View icons: http://entypo.com/

## Prerequisites
For easiest implementation of this or any other icon font it is reccomended you install the Vanilla theme when you start to style your applicaton.
https://appstore.home.mendix.com/link/app/2681/Mendix/Vanilla-Theme

## Configuration
Here are the steps to incorporate this icon font into your project. 

### Step 1
Copy and paste the fonts folder into the following folder 
your_project_folder/theme/styles/css
### Step 2
Copy and paste the _entypo.scss file into the following folder your_project_folder/theme/styles/sass/lib/components
### Step 3
Open the lib.scss file under your_project_folder/theme/styles/sass and under the bottom add the following line:
```
@import "components/entypo";
```
to include the _entypo.scss file partial into the outputed css file

## Example usage
If you want to show the entypo camera icon to show up on any mendix element add the following text to the class field under the mendix elements properties box: 
```
entypo entypo-camera
```