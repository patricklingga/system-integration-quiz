# system-integration-quiz

## 1. Create your own fork
<img width="1573" height="342" alt="image" src="https://github.com/user-attachments/assets/23de9b96-8cc2-4260-ba78-317f807b13ea" />

## 2. Clone your own repository
```
git clone https://github.com/<your-account>/system-integration-quiz
```

## 3. Create a file <your-name>.txt and fill out the answer of your Quiz for example:
```
File name: patrick.txt
1. A
2. B
3. C
4. D
5. E
```

## 4. Create a branch <your-name>-branch
```
git checkout -b <your-name>-branch

For example: git checkout -b patrick-branch
```

## 5. Add, commit, and push your branch
```
git add <your-name>.txt
git commit -m "Add <your-name>'s Answer"
git push origin <your-name>-branch
```

## 6. Create a pull request from your forked repository to the patricklingga:patrick-branch
<img width="1150" height="349" alt="image" src="https://github.com/user-attachments/assets/2575fe37-fff5-4e65-91e0-4e93ba6ac7f9" />

<img width="1161" height="683" alt="image" src="https://github.com/user-attachments/assets/8d4e58f0-2763-494b-9bea-02ac4aa6402f" />

I will receive your pull request and grades it from there
<img width="1589" height="448" alt="image" src="https://github.com/user-attachments/assets/cd37fb00-2274-420a-9c85-96408b882245" />


# QUESTIONS FOR THE QUIZ
1. What is the primary purpose of using branches in Git?
```
A. It ensures that only one developer can make changes at a time.
B. It allows developers to experiment or build features independently without affecting the main project.
C. It automatically merges updates from all developers into the main branch.
D. It prevents any modification to the source code once the project is published.
```

2. What happens if two developers modify the same line of code in different branches and try to merge them?
```
A. Automatically overwrite the first developer’s changes with the second’s version.
B. Combine both lines into one and merge automatically.
C. Pause the merge process and flag a merge conflict requiring manual resolution.
D. Accept the first merge and ignore all subsequent changes.
```

3. In GitHub, what is a Pull Request (PR) mainly used for?
```
A. It downloads updates from the remote repository to a local machine.
B. It requests permission to overwrite another contributor’s branch.
C. It proposes integrating changes from one branch into another after peer review.
D. It automatically merges all branches without requiring approval.
```

4. When working concurrently on a shared GitHub repository, why is it recommended that each developer works in their own feature branch instead of editing main directly?
```
A. Because branches are faster to upload to GitHub, in a big system project, it will take a lot of time to actually upload it to the main branch.
B. Because it prevents repository cloning errors.
C. Because it isolates their work, reducing the chance of overwriting others’ code.
D. Because only feature branches can be merged into the main repository, the main cannot be updated without the branch.
```

5. Why do teams often protect the main (or master) branch in collaborative projects?
```
A. To prevent it from being cloned by unauthorized users.
B. To restrict direct commits and ensure changes are reviewed and tested through pull requests.
C. To allow automatic deletion of feature branches after merging.
D. To make sure contributors cannot create new branches.
```
