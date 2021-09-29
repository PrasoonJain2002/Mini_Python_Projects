# Hacktoberfest-2021 🎉
https://hacktoberfest.digitalocean.com/

![Screenshot (418)](https://user-images.githubusercontent.com/47255445/135327252-3ae00ef0-1f12-4fd7-b690-07559082d1ac.png)


## What is Hacktoberfest?? 

Hacktoberfest is a month (takes place from October 1-October 31 every year) long virtual festival event to celebrate open source contributions presented by DigitalOcean and DEV. https://hacktoberfest.digitalocean.com/

Hacktoberfest is open to everyone. To get the Hacktoberfest 2021 T-Shirt you need to make four Pull Requests to those projects/repositories which have hacktoberfest label, between October 1,2021 to October 31,2021 in any time zone . Before that make sure you have visited the official website and registered [here](https://hacktoberfest.digitalocean.com/)


## How to contribute??

Submit your pull request here for Hacktoberfest-2021 . You can submit your Python mini projects or any solved programming questions in Python language only.
Repository Link: https://github.com/neha07kumari/Mini_Python_Projects

## Rules for Contributing to this Repository

1. Make sure to go to the right folder .
2. If you are adding a program in python ,then go to Programming_in_Python and follow the below steps:
```bash
   <algorithm name>/
   ├── <implementation file> (With commented sample input/output. In Python Lnaguage only.)
   ```
   I have added a sample file for your reference .
3.If you are adding a mini project in python , then go to Projects_in_Python and follow the below steps:
```bash
  <project name>/
  ├── <project output> (Add the screenshot of the output.)
  ├── <project code files> (can add as many required code files.)
  ```
  I have added a sample file for your reference.
4. On Making a Pull Request make sure that you write about your valuable contribution(a short intro or note about it). 


## Rules
* Pull requests can be made in any participating GitHub or GitLab hosted repository/projects. Look for the 'hacktoberfest' topic to know if a project is participating in Hacktoberfest.
* You can [sign up](https://hacktoberfest.digitalocean.com/) anytime between October 1 and October 31. Just be sure to sign up on the official Hacktoberfest website for your pull requests to count.

## Details

* The pull request must contain commits you made yourself.
* If a maintainer reports your pull request as spam, it will not be counted toward your participation in Hacktoberfest.
* If a maintainer reports behavior that’s not in line with the project’s code of conduct, you will be ineligible to participate.
* A pull request is considered approved once it has an overall approving review from maintainers, or has been merged by maintainers, or has been given the    'hacktoberfest-accepted' label.

# So, why Wait?? Let's Start😁  

## How to Begin your Contribution

* Add your name to the CONTRIBUTORS.md file using following model

```markdown
Name: [YOUR NAME](Github Link)
Place: city you belong to
About: Short Intro (Optional)
```
## Instructions:

*Make sure you have a GitHub account. In case you don't have one, you can create your account by visiting https://github.com/ and clicking on ``Sign up`` option at the top right corner.*

### 1. Register yourself for Hacktoberfest 
###### Link to register: https://hacktoberfest.digitalocean.com/
Click on "Start Hacking" and add your GitHub account.


### 2. Star and Fork this Repository
###### You can star and fork this repository on GitHub by navigating at the top-right of this repository.

![Screenshot (419)](https://user-images.githubusercontent.com/47255445/135331429-7384984b-c01f-4fed-9bfa-9eac472a5aed.png)


### 3. Clone the Repository

Use the `git clone`  command along with the URL that points to your fork of the repository.
Example:
git clone https://github.com/<Your_Username>/Mini_Python_Projects
`git clone https://github.com/your-username/Hacktoberfest.git`


### 4. Create a New Branch

Now, we’ll create our new branch with the git branch command. Make sure you name it descriptively so that others working on the project understand what you are working on.

##### `git branch new-branch`

Now that our new branch is created, we can switch to make sure that we are working on that branch by using the git checkout command:

##### ` git checkout new-branch `

Once you enter the git `checkout` command, you will receive the following output:

######  `Output:`
#####  `Switched to branch 'new-branch' `

At this point, you can now modify existing files or add new files to the project on your own branch.

#### Make Changes Locally

Once you have modified existing files or added new files to the project, you can add them to your local repository, which you can do with the git add command. Let’s add the -HelloWorld flag to add all changes that we have made:

##### ` git add -HelloWorld ` or ` git add . `

Next, we’ll want to record the changes that we made to the repository with the git commit command.

*The commit message is an important aspect of your code contribution; it helps the other contributors fully understand the change you have made, why you made it, and how significant it is. Additionally, commit messages provide a historical record of the changes for the project at large, helping future contributors along the way.*


If you have a very short message, you can record that with the -m flag and the message in quotes:

###### ` Example: `
##### ` git commit -m "Updated Readme.md" `

###### At this point you can use the git push command to push the changes to the current branch of your forked repository:
###### ` Example:`
##### ` git push --set-upstream origin new-branch `

### 5. Update Local Repository

*While working on a project alongside other contributors, it is important for you to keep your local repository up-to-date with the project as you don’t want to make a pull request for code that will cause conflicts. To keep your local copy of the code base updated, you’ll need to sync changes.*

We’ll first go over configuring a remote for the fork, then syncing the fork.

### 6. Configure a Remote for the Fork

Next up, you’ll have to specify a new remote upstream repository for us to sync with the fork. This will be the original repository that you forked from. you’ll have to do this with the git remote add command.

##### ` git remote add upstream https://github.com/neha07kumari/Mini_Python_Projects.git `

In this example, // upstream // is the shortname we have supplied for the remote repository since in terms of Git, “upstream” refers to the repository that you cloned from. If you want to add a remote pointer to the repository of a collaborator, you may want to provide that collaborator’s username or a shortened nickname for the shortname.

### 7. Sync the Fork

Once you have configured a remote that references the upstream and original repository on GitHub, you are ready to sync your fork of the repository to keep it up-to-date.
To sync your fork, from the directory of your local repository in a terminal window, you’ll have to use the // git fetch // command to fetch the branches along with their respective commits from the upstream repository. Since you used the shortname “upstream” to refer to the upstream repository, you’ll have to pass that to the command:

##### ` git fetch upstream `

Switch to the local master branch of our repository:

##### ` git checkout master `

Now merge any changes that were made in the original repository’s master branch, that you will access through your local upstream/master branch, with your local master branch:

##### ` git merge upstream/master `

### 8. Create Pull Request

At this point, you are ready to make a pull request to the original repository.

Navigate to your forked repository, and press the “New pull request” button on your left-hand side of your Repo page.

# Hurray!🎉👍 You Have Almost Done It!! Wait for it to get merged in the main repo.


```

  if (needHelp === true) {
     var emailId = "2211nehakumari@gmail.com";
     // email is the best way to reach out to me.
     sendEmail(emailId);
  }

```

  [![Instagram](https://img.shields.io/static/v1.svg?label=follow&message=@neha7_kashyap&color=grey&logo=instagram&style=flat&logoColor=white&colorA=critical)](https://www.instagram.com/neha7_kashyap/) [![LinkedIn](https://img.shields.io/static/v1.svg?label=connect&message=@neha-kumari-09415a16b/&color=9cf&logo=linkedin&style=flat&logoColor=white&colorA=blue)](https://www.linkedin.com/in/neha-kumari-09415a16b/) [![Twitter](https://img.shields.io/static/v1.svg?label=connect&message=@Neha_kumari_7&color=grey&logo=twitter&style=flat&logoColor=white&colorA=critical)](https://twitter.com/Neha_kumari_7)

***Glad to see you here! Show some love by [starring](https://github.com/neha07kumari/Mini_Python_Projects/) this repo.***

-----

```

  if (isAwesome) {
    // thanks in advance :p
    starThisRepository();
  }

```

******

              
 ## HAPPY HACKING!😁😁
 ## HAPPY CODING!!👩‍💻👩‍💻
