# sample-project1
### Setting Up the Repository
- Created a new public repository on GitHub: `sample-project`.
- Clone the repository to my local machine: `git clone https://github.com/yourusername/sample-project.git`.

### Initial Commit
- Created a `README.md` file with a project description.
- Added a `.gitignore` file to ignore unnecessary files.
- Commited changes: `git add.`, `git commit -m "Initial commit"`, `git push origin main`.

 Feature Branch
- Created a new branch: `git checkout -b feature/add-greeting`.
- Added a file: `greeting.txt` with "Hello, World!".
- Commit and push: `git commit -m "Add greeting"`, `git push origin feature/add-greeting`.

 Pull Request
- On GitHub, open a pull request from `feature/add-greeting` to `main`.
- Request a code review.

 Merge Pull Request
- Wait for approval, then merge the pull request on GitHub.

Branching and Merging with Conflicts
- Create a new branch: `git checkout -b feature/add-farewell`.
- Add a file: `farewell.txt` with "Goodbye, World!".
- Commit and push.
- Create and merge a pull request for `feature/add-farewell`.

 Simulated Conflict
- On `feature/update-greeting`, update `greeting.txt` to "Hello, Universe!".
- Pushed changes.
- On `main`, update `greeting.txt` to "Hi, World!" and push.
- Create a pull request for `feature/update-greeting` to `main`, resolve the conflict.

 Tagging and Releases
- Tagged the `main` branch: `git tag v1.0`.
- Created a release on GitHub using `v1.0`, with release notes.
