# [Big D](http://bigdbarbecue.com)

Big D's website is built on a variety of modern web technologies.

* Middleman: [http://middlemanapp.com/](http://middlemanapp.com/)
* Sass: [http://sass-lang.com/](http://sass-lang.com/)
* Compass: [http://compass-style.org/](http://compass-style.org/)
* JQuery: [http://jquery.com/](http://jquery.com/)
* JQuery UI: [http://jqueryui.com/](http://jqueryui.com/)
* Fullpage.js: [https://github.com/alvarotrigo/fullPage.js](https://github.com/alvarotrigo/fullPage.js)
* Bootstrap 3 Modal: [http://getbootstrap.com/javascript/#modals](http://getbootstrap.com/javascript/#modals)

## Features

* HTML5 ready.
* Cross-browser compatible (Chrome, Firefox, IE8+, Opera, Safari).
* Includes [Normalize.css](http://necolas.github.com/normalize.css/) for CSS
  normalizations and common bug fixes.
* [jQuery](http://jquery.com/) 2.0.3.

## Quick start

This project assumes that you have working knowledge of the above technologies and have the appropriate software and technologies installed. Commands should be run from the terminal.

1. Clone the git repo — `git clone https://github.com/karlcarstensen/bigd.git`.
2. From the master branch run `bundle install`. This will ensure that you have the proper gem files.
3. To run the project `middleman`
4. Changes will be reflected automatically on [http://0.0.0.0:4567/](http://0.0.0.0:4567/)

## Changes workflow

1. Create a topic branch for your updates.
`git checkout -b your-topic-branch-name`

2. Make any changes or updates to the code.

3. Commit, with a meaningful commit message that describes the updates.
`git commit -m "Here is a detailed description of the changes made on this branch`

4. Push to the topic branch on the remote server and issue a pull request for a code review and feedback.

## Deploying code

The best way to deploy code is to let the built-in compiler create the website for you. To do this, follow the directions below.

1. Make sure that you have the latest version of the project, any changes have been committed and approved, and you are on the master branch.
2. Run `middleman build`
3. When the compiler completes, copy the contents of the build directory to the root of your server in their entirety. Do not copy the build directory itself, only the contents of the folder.

## Contributing

If you would like to contribute or optimize this project, please follow the above process (fork the repository, create a topic branch, and issue a pull request with your changes). A member of the project will review it quickly and either merge it or provide feedback regarding the commit.

– Big D
