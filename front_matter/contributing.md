# How to Contribute

Follow these steps **only once**:
1. Go to https://github.com/campa-consortium/lattice-standard.

2. Click the pulldown arrow next to `Fork`, click `Create a new fork`, and specify your GitHub username in the `Owner` field (e.g., "cemitch99").

3. Click `Code` to view and copy the URL of your fork 
(e.g., https://github.com/cemitch99/lattice-standard.git)

4. On your local machine, from the terminal, clone your fork:
```
git clone https://github.com/cemitch99/lattice-standard.git
```

Follow these steps **each time you submit a pull request**:
1. Change into the working directory for your local repo:
```
cd lattice-standard
```

2. Create a new branch with a descriptive name for the desired changes (e.g., "add_template"):
```
git checkout -b add_template
```

3. Make the desired changes to the local files.
For example, add a new file "pull_request_element_template.md"

4. View the proposed changes via `git status` (optional).

5. Add the changes to your local staging area:
```
git add pull_request_element_template.md
```

6. Commit the changes to your local repo, including an informative message:
```
git commit -m "Add element template."
```

7. Push your changes to the remote repository:
```
git push origin add_template
```

8. Follow the link that is generated to open a new pull request on GitHub that includes these changes, e.g., go to  https://github.com/cemitch99/lattice-standard/pull/new/add_template.

9. Add a title and additional information relevant to the pull request (as needed).
