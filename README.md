[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/2.0.0/active.svg)](https://github.com/xoopscube/xcl)
![License GPL](https://img.shields.io/badge/License-GPL-green)
![X-Updare Store](https://img.shields.io/badge/X--Update%20Store-Pending-red)

## ///// — XLayout Flexbox Helper :: Themes & Modules Templates

![alt text](https://repository-images.githubusercontent.com/485308409/7da19feb-cc5b-43ae-bf66-6d8d24c9a2)
  

---

XLAYOUT | UI Flexbox Helper
------------ | -------------
Description | XLayout is based on CSS flexbox specification originally implemented in Flex layout attribute
Render Engine | Smarty v2 and Smarty v3
Version | 2022
Author | @gigamaster Nuno Luciano (XCL23)
Copyright | 2011-2022 Author
License | GPL


##### :computer: The Minimum Requirements



          Apache, Nginx, etc. PHP 7.2.x
          MySQL 5.6, MariaDB  InnoDB utf8 / utf8mb4
          XCL version 2.3.+



-----


## Overview   

Render Engine - Smarty is a template engine for PHP, facilitating the separation of presentation (HTML/CSS) from application logic.  
This implies that PHP code is application logic, and is separated from the presentation, making it easier to customize theme and templates.

[What is Smarty v2](https://www.smarty.net/docsv2/en/what.is.smarty.tpl)    
[Smarty 3 Overview](https://www.smarty.net/v3_overview)    


### Features


- Flexbox layout
- Responsive theme
- CSS Custom properties
- Localization    


### Install or Update Themes

1. Select a branch from this repo and, from the dropdown button "Code" select Clone or Download zip.  
2. Extract and upload the folder "theme-name" to your domain, eg.: public/html/themes/theme-name/*.*  
3. From the Administration dashboard, activate the Theme (checkbox/select).  
  
Or, from the Administration dashboard, click "X-Update Manager" to automatically download and install    
from the Theme Store for free.



## Feature Branch Workflow

Branches are used to build independent Themes, Templates, Components and features.  
Following the core idea behind the **Feature Branch Workflow** each theme development   
takes place in a dedicated branch instead of the main branch. This encapsulation makes   
it easy for multiple themes built with a specific CSS framework or xLayout.

### 1 - Clone the repository   

You can clone the repository to create a local copy on your computer.  
This gives us access to all branches in this repository.

``` 
git clone https://github.com/xoopscube/xcl-themes-xlayout.git
```

> When you clone a repository, you get the **main** branch by default.   
> This means you will have to checkout another branch yourself.   
> You can easily switch between each branch using GitHub Desktop.  



### 2 - Clone a Specific Branch

There are two ways to clone a specific branch. You can either:

a) Clone the repository, fetch all branches, and checkout a specific branch.
b) Clone the repository and fetch only a single branch.  

#### Option One  

``` 
git clone --branch <branchname> <remote-repo-url>
```

or using **-b** an alias for --branch

``` 
git clone -b <branchname> <remote-repo-url>
``` 

#### Option Two

``` 
git clone --branch <branch-theme-name> --single-branch <remote-repo-url>
``` 

or using **-b** an alias for --branch

``` 
git clone -b <branch-theme-name> --single-branch <remote-repo-url>
``` 

> This performs the same action as option one, except that the **--single-branch** option   
> only fetch the files from the specified Theme branch without fetching other branches.


**Learn more...**   
  
- [Git Basics - Getting a Git Repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)  
- [GitHub - Cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)  




#### Theme Folder Structure

```bash
themes
└───theme-name
    │   CHANGELOG.md
    │   manifesto.ini.php
    │   README.md
    │   screenshot.png
    │   theme.html
    │
    ├───component
    ├───css
    ├───images
    ├───js
    ├───language
    └───templates
        ├───d3forum
        ├───eguide
        ├───legacy
        ├───message
        ├───pico
        ├───profile
        └───user
```


License
-------

The Themes are released under a BSD or Creative Commons license.  
Some Components and Plugins can be released under licenses that   
guarantee a certain specific set of freedoms - GPL, MIT, etc.  

[LICENSE](LICENSE)

Code contributions
----------------

If find a bug or it's a feature that you think would need to be discussed please open an issue first,   
otherwise, you can follow this process:

1. Fork the project [Fork a Repo](http://help.github.com/fork-a-repo/)
2. Create a feature branch : `git checkout -b my_branch`
3. Push your changes to your new branch : `git push origin my_branch`
4. Initiate a pull request [About Pull Requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
5. Your pull request will be reviewed and hopefully merged :)

Have Fun ^_^/


