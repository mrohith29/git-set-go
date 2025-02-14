[comment]: # (Working in Teams.)

What Will You Learn in This Session?

---

✅ Understand how GitHub helps in team collaboration

✅ Learn what Forking is and how it works

✅ Learn about Pull Requests and how they help in teamwork

✅ Explore these concepts with a fun analogy—because learning should be fun! 😄

---

# What is Forking?

---

Forking in GitHub means creating a copy of someone else’s repository into your own GitHub account. This allows you to make changes without affecting the original project.

---

- Your friend’s notebook = The original GitHub repository
  
- The photocopy you made = Your forked repository
  
- Any changes you make = Your improvements or contributions

---

### How to Fork a Repository

---

1. Go to the repository you want to fork on GitHub.
2. Click the "Fork" button at the top right of the page.
3. Select your GitHub account where you want to create the forked repository.
4. GitHub will create a copy of the repository in your account.

---

# What is a Pull Request (PR)? 

---

A Pull Request (PR) is a way to propose changes to the original repository. Once you’ve made improvements in your forked repo, you can send a Pull Request to the owner of the original repo, asking them to merge your changes.

---

- Sending the updated notes = Creating a Pull Request

- Your friend reviewing your changes = Code review

- Your friend accepting and adding your updates = Merging the Pull Request

---

### How to Create a Pull Request

---

1. Make sure you have forked the repository and cloned it to your local machine.

2. Make your changes and commit them:
   ```bash
   git add .
   git commit -m "Description of my changes"
   ```

---

3. Push your changes to your forked repository:
   ```bash
   git push origin my-feature-branch
   ```
4. Go to the original repository on GitHub.
5. Click the "New Pull Request" button.
6. Select the branch with your changes and create the Pull Request.
7. Add a descriptive title and comment for your Pull Request, then submit it.

---

### How Do Forks & Pull Requests Work Together?

---

1.  You fork a repository (make a copy of someone’s project).

2. You make changes to the forked version in your account.

3. You create a Pull Request (PR) to propose your changes to the original repo.

4.  The repo owner reviews your changes and may ask for some refinements.

5. If everything looks good, they merge your changes into the main project.

