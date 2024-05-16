# Git and GitHub collaboration through the forking method

## Contributing to a Frontend Web Application built with React
This document outlines the guidelines for contributing to our project. By participating, you agree to abide by these guidelines for a healthy and productive collaboration.

### Getting Started
1. Fork the repository: Click the `Fork` button in the upper right corner of the repository's page on GitHub to create a copy of the project in your GitHub account.

2. Clone the repository: Clone the forked repository to your local machine using the following command:
`git clone https://github.com/your-username/project-name.git`

3. Set up the upstream remote: Navigate to the directory of the cloned repository and set up an upstream remote to keep your local repository synced with the original project. Use the following command:
`git remote add upstream https://github.com/original-owner/project-name.git`

4. Create a new branch: Before making any changes, create a new branch for your feature or bug fix. Use a descriptive name for your branch, such as feature/new-feature, feature/login-page or bugfix/issue-123.
`git checkout -b <branch-name>`

5. Making Changes
    - To get started on the project
        - In the project directory, run `npm install` in the terminal
        - Run `npm start`
    - Work on your changes: Make your desired changes to the codebase using your preferred editor or IDE.

6. Commit your changes: Once you're satisfied with your changes, commit them to your local repository with descriptive commit messages. Use the following command:
`git add .`
`git commit -m "Your descriptive commit message"`

7. Sync your fork: Before pushing your changes, make sure your fork is synced with the original repository to avoid merge conflicts. Use the following commands:
`git fetch/pull upstream`

8. Push your changes: Push your committed changes to the forked version on your GitHub.
`git push origin <branch-name>`
##### NB: Never push directly to the `main` branch :x: :x:

9. Submitting Changes
    - Create a pull request: Navigate to the forked version on your GitHub and select the branch containing your changes on the right.
    - Select which branch you want to merge your code(feature/branch) with on the left.
    - Click the "New pull request" button to open a new pull request (PR).
    - Describe your changes: Provide a descriptive title and summary of your changes in the PR description.
    - Include any relevant information that reviewers may need to know.
    - Review and address feedback: Collaborate with reviewers to address any feedback or suggestions. Make additional changes to your code as necessary.

10. Merge your pull request: Once your PR has been approved and all discussions have been resolved, a project maintainer will merge your changes into the main/staging/dev branch.

### Code of Conduct / Rules / Guidelines
Please adhere to our Code of Conduct in all interactions related to this project.
1. Use only `npm` as package manager.
2. Proper and adequate documentation of some of your important logic(complex) code in form of comment.
   - E.g Give a short(one line) and descriptive comment of your code/logic/feature.
3. The main github repository branch is `main` and not `master`. :x: :x: `master`
4. ALways create a feature-branch. Do not push directly to the `main/staging/dev` branch :x: :x:

## NB
-  This `README.md` file would updated down the line when there need be. Please endeavour to check it out every now and then to stay updated for proper collaboration.
-  On no occassion are you to make changes to this `README.md` file by yourself. If there need a rule, guideline or anything you might want in the `README.md` file, please communicate to the appropriate authorities.


### Additional Resources
1. Project Wiki: Additional documentation and resources related to the project.
2. Issue Tracker: Report bugs or request new features.
3. Discussion Board: Engage with the community and ask questions.

Thank you for contributing to the Web Application! Your efforts help make our project better for everyone.

### Happy collaborating!!!
