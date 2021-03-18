# Contributing to Atrium

Thank you very much for taking your time to contribute :smiley:

Following a few guidelines so that others can quickly benefit from your contribution.

### Table of Content: 

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute) 
- [Your First Code Contribution](#your-first-code-contribution)
- [Coding Conventions](#coding-conventions)
- [Pull Request](#pull-request)



## Code of Conduct
This project and everyone participating in it is governed by [Code of Conduct](https://github.com/robstoll/atrium/tree/master/.github/CODE_OF_CONDUCT.md). 
By participating, you are expected to uphold this code. Please report unacceptable behaviour to info@tutteli.ch

## How to Contribute
- Star this repository if you like it.
  
- Found a bug?  
  [Open an issue](https://github.com/devops-education/Challenges-in-Devops-Education/issues/new?template=bug_report.md).
  
- Missing a topic?  
  [Create a topic request](https://github.com/devops-education/Challenges-in-Devops-Education/issues/new?template=feature_request.md&title=[Feature]).
  
- Found spelling mistakes?  
  Nice catch :mag: Please fix it and create a pull request.
     
- You have other ideas how Atrium could be improved?  
  Contact us on 
  [slack](https://kotlinlang.slack.com/messages/D3CL4DDLG/),
  we are looking forward to your ideas.

In any case, if you are uncertain how you can contribute, then contact us on 
[slack](https://kotlinlang.slack.com/messages/D3CL4DDLG/)
and we will try to figure it out together :smile:

## Your First Code Contribution
Fantastic, thanks for your effort! 
 
The following are a few guidelines on how we suggest you start.
 
1. Fork the repository to your repositories (see [Fork a repo](https://help.github.com/en/articles/fork-a-repo) for help). 
2. Read up the [Coding Conventions](#coding-conventions) (there are only 5 points).

Perfect, you are setup and ready to go. 
Have a look at [help wanted issues](https://github.com/devops-educatio/Challenges-in-Devops-Education/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
where [good first issues](https://github.com/devops-educatio/Challenges-in-Devops-Education/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
are easier to start with.
Please write a comment such as `I am working on this` in the issue,
this way we can assign the task to you (so that others know there is already someone working on the issue)
and it gives us the chance to have a look at the description again and revise if necessary.

<a name="git"></a>
*Git*  

Dealing with Git for the first time? Here are some recommendations for how to set up Git when working on an issue: 
- create a new branch for the issue using `git checkout -b <branch-name>` (preferably, the branch name
  should be descriptive of the issue or the change being made, e.g `#108-path-exists`.) Working
  on a new branch makes it easier to make more than one pull request.
- add this repository as a remote repository using
 `git remote add upstream https://github.com/devops-education/Challenges-in-Devops-Education.git`. You will use this to
  fetch changes made in this repository.
- to ensure your branch is up-to-date, rebase your work on
  upstream/master using `git rebase upstream/master` or `git pull -r upstream master`.
  This will add all new changes in this repository into your branch and place your
  local unpushed changes at the top of the branch.

You can read more on Git [here](https://git-scm.com/book/).

Contact us on
[slack](https://kotlinlang.slack.com/messages/C887ZKGCQ/)  
whenever you need help to get up and running or have questions or simply write in the issue.

We recommend you create a pull request (see [About pull requests](https://help.github.com/en/articles/about-pull-requests) for help)
in case you are not sure how you should do something. 
This way we can give you fast feedback regarding multiple things (style, does it go in the right direction etc.) before you spend time for nothing.
Prepend the title with `[WIP]` (work in progress) in this case and leave a comment with your questions.

Finally, when you think your PR (short for pull request) is ready, then please:

1. read the [Pull Request Checklist](#pull-request-checklist) 
2. Create your first pull-request
3. 👏👏👏 you have submitted your first code contribution to Atrium :blush:

## Pull Request
Please make sure you can your pull request is rebased on the [latest commit on master](https://github.com/robstoll/atrium/commits/master) before you create a pull request.
