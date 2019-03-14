# EEECS Lego Lab - Template Project

USe this repository for the creation of new Lego Lab GitHub repositiories. Customise this README so it is suitable for your project, and allows anyone to contribute to your project.

## Getting Started

First, fork this repository. You can do this by pressing the 'Fork' button at the top right of this screen. This will copy this repository to your own account, so you can change it as needed and add your project files.

### Cloning using Git

Once you have forked the repository, you can download it to your computer. This allows you to edit the files and add new files, before reuploading back to GitHub.

Use the green 'Clone or Download' button at the top right of your forked repository. Copy the URL - it should look similar to the one below - and then use the 'git clone' command:
```
git clone https://github.com/eeecslegolab/template.git
```
Git will then download the entire repository to a new folder.

## Using this Repository

Once you have your forked repository downloaded, you can add your code and files, and edit the existing files as you need.

* README.md
  - Required
  - The file you're reading now - is shown when the repository is opened online and should contain lots of information about your project.
* NOTES.md
  - Essential
  - Outline pitfalls/challenges you encountered during development and how you overcame them.
* LICENSE.md
  - Required
  - What kind of license do you want for this project? Check [this website](https://choosealicense.com/).
* CONTRIBUTING.md
  - Optional
  - Describe how other can contribute to the project. TODO lists, code styes, or any other requests go here.
* INSTALLATION.md
  - Required
  - Describe how to install the project and get it running.
* .gitignore
  - Highly Recommended
  - The .gitignore file will tell Git which files to ignore (and not to try and upload). Temporary IDE files or build files that aren't needed should be added to this file.
  
## Uploading to GitHub

Every time you add new files and code, you will need to tell Git to upload these changes to GitHub. This is done with three commands (though can be more if, for example, two people edit the same file at the same time and both try to upload their conflicting changes).

First, find all the changed/new files and prepare them to be added to the respository with
```
$ git stage *
```

Next, create a new commit. Commits are saved versions of the project at that time, allowing you to see how the project changes over time and go back in time if something doesn't work as it should.

```
$ git commit -m "write a message describing what you've done here"
```
Now we've saved our changes locally, we need to upload them to GitHub (or any other Git host, such as the EEECS Gitlab):

```
$ git push -u origin master
```
Git might ask for your account details, and then will upload your project.

## Built With

* [Markdown](https://en.wikipedia.org/wiki/Markdown) - Text formatting

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Hector Southern** - *EEECS Lego Lab Demonstrator* - [hectorsouthern](https://github.com/hectorsouthern)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* N/A
