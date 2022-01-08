## Guidance on how to contribute

If you are are first timer I recommend reading from [here](#your-first-contribution).

Else you can read the first three paragraphs and start contributing.

The following is a personal project and shall not be used for any personal business or as such
use case without asking the maintainer and so.
There are two primary ways to help:
 - Using the issue tracker, and
 - Changing the code-base.

## Using the issue tracker

Use the issue tracker to suggest feature requests, report bugs, and ask questions.
This is also a great way to connect with the developers of the project as well
as others who are interested in this solution.

Use the issue tracker to find ways to contribute. Find a bug or a feature, mention in
the issue that you will take on that effort, then follow the _Changing the code-base_
guidance below.

## Changing the code-base
Generally speaking, you should fork this repository, make changes in your own fork, and then submit a pull request.
All new code should have associated unit tests that validate implemented features and the presence or lack of defects.
Additionally, the code should follow any stylistic and architectural guidelines prescribed by the project. 
In the absence of such guidelines, mimic the styles and patterns in the existing code-base.


## General Instructions

- Please follow all the Code of Conduct rules.
- Document your changes in the code properly with comments.
- Mention how your change has impacted the project's working and how benefical it was.
- That's it folks dont want to restrict to endless possibilities.

# Your First Contribution

Is this your first time contributing to an open source project? If yes, Welcome!!✨🎉💃🏾 Here is a [great tutorial](https://app.egghead.io/playlists/how-to-contribute-to-an-open-source-project-on-github) on how to contribute to an open source project.

At the point you are ready to take on the world of open source contribution!!.

You must have seen a bug or problem you can fix, this is when you open a new issue for that problem. Let's do it together.

## Steps to open a new issue

- **Step 1:** Navigate to the issues naviagtion button. See below 👇

*(Screenshot: Issue navigation button)*

- **Step 2:** Scan through the currently opened issues to see if your issue(s) has been listed earlier. See below 👇

*(Screenshot: Browse existing issues)*

- **Step 3:** If your issue hasn't been listed yet, click on the New issue button at the top right corner to add your new issue. See below 👇

*(Screenshot: New issue button)*

- **Step 4:** Time to add your amazing issue. You add the title and a brief description of the issue. For further explanation, images can be added as well. See below 👇

*(Screenshot: Add title and description)*

- **Step 5:** Submit the issue. See below 👇

*(Screenshot: Submit issue)*


Hurray, you just made added your first issue. The maintainers will now review your issue and you will either get assigned to the issue, have it closed or a comment will be dropped for you.

You have been assigned an issue 🥂 and are confused 😵 about where to go from here, follow this guide below to make your changes and pull request 🍾.

## Getting Started

Fork the repository. See below 👇

*(Screenshot: Fork button)*

Clone the repository you forked above. See below 👇

*(Screenshot: Clone repository)*

Using the command below, you can clone the repo.

```
git clone https://github.com/YOUR_USERNAME/Ai-based-Ecommerce-web-app.git
```

Navigate to the cloned directory and then to client folder  using command line. See below 👇

```
cd Ai-based-Ecommerce-web-app
cd client
```

Install all the dependencies. See below 👇

```
npm i
```

Go to server file file and install all dependencies. See below 👇
```
cd server
npm i 
```
Then run the server using the command given below. See below 👇

```
node server.js
```
Or
Install nodemon and then run the server using nodemon like this 👇
```
npm i nodemon
nodemon server.js
```

Then open the project in any IDE of your choice.

Then go to client and go the src, then to utils, and then to axios.js.Then, change the base url as 'http://localhost:9000/', See below 👇 
```js
const instance =  axios.create({
    baseURL: 'http://localhost:9000/',
})
```

Then you are set to work with my project 🎉


I have made a dummy test account for to login :- 
Username - test,
Password  - 1234


Make a new branch. See below 👇

*(Screenshot: Create branch)*

```

git checkout -b "Your Branch Name"
```

A good branch name would begin with the issue ticket and the assigned issue. See below 👇

```
// #343 is the issu ticket number and make a request is the assigned issue na

git checkout -b "#343-make a request"
```

You are all set!! 🍾🎉. You can now make your changes locally. Once you are done making all your changes, you can now push code and make a pull request.

## Steps to making a pull request

You have to switch to the main branch and make sure it's up to date with the upstream main branch. To do so, use the following commands below.

```
git remote add upstream https://github.com/UPSTREAM_OWNER/Ai-based-Ecommerce-web-app.git
git checkout main
git pull upstream main
```

You can now update your branch from your local copy of main, and push it!. See how below. 👇

```
git checkout #343-make a request
git rebase main
git push --set-upstream origin #343-make a request
```

Hurray!!, we are done with the hard part. Head to github to make the pull request Github will check for conflicts and if non is found, you can make the pull request and the maintainers will review your pull request to have it merged or make a comment on it.

# Code review process

The maintainer of Ai-based Ecommerce Web App looks at Pull Requests on a regular basis and carries out merging or comments on the requests. You can close a pull request if it isn't showing any activity after two weeks.

## Commit messages 

Ai-based Ecommerce Web App has certain conventions that should be adopted when contributing.

### Commit message conventions.

- Commit test files with `test: ...` prefix
- Commit bug fixes with `fix: ...` prefix
- Commit new features with `feat: ...` prefix
- Commit changes to `package.json`, `.gitignore` and other meta files with `chore(filenamewithoutext): ...`
- Commit changes to README files or comments with `docs: ...`
- Cody style changes with `style: standard`
