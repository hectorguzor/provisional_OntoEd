# provisional_oed

This repository is designed for students learning ontology development. Its aim is to help students gain and enhance their ontology development skills by contributing to a provisional Ontology of Education (OED), which employs <a href="https://github.com/bfo-ontology/BFO-2020">the Basic Formal Ontology (BFO)</a> as a higher-order ontology.

The primary focus of OED is to define and represent entities and relationships in education, ranging from K-12 to postsecondary institutions. By defining classes such as organization, enrollment, assignment, assessment, and more, oed helps education professionals communicate clearly about educational services. This clear and precise vocabulary enables educational institutions to annotate, integrate, and analyze data to improve educational outcomes.

Students contributing to OED identify areas in need of development within the ontology and implement changes consistently, adhering as closely as possible to the best practices in ontology development as outlined by <a href="https://obofoundry.org/principles/fp-000-summary.html">the OBO Foundry</a>. Additionally, students are responsible for reviewing changes to ensure they accurately reflect the latest understandings of educational practices.

# Development

We use git and GitHub to develop OED. There's a lot of good documentation on both:

<br>Here is the <a href="https://git-scm.com/">git website</a> with files and documentation<br>
Also check out the <a href="https://docs.github.com/en/get-started/using-github/github-flow">GitHub work flow  website</a>

# how_to_help

### 1. Create a Fork of the Repository
   - If you don’t have write access to the repository, first **fork** the repository.
   - Go to the repository page and click the "Fork" button in the top-right corner.
   - This creates your own copy of the repository where you can make changes safely.

### 2. Clone the Repository (Optional)
   - If you prefer working locally, clone your fork:
     ```bash
     git clone https://github.com/your-username/repository-name.git
     ```
   - Navigate into the repository directory:
     ```bash
     cd repository-name
     ```

### 3. **Create a New Branch**
   - Always work on a new branch when recommending changes. This isolates your work from the `main` branch:
     ```bash
     git checkout -b recommended-changes
     ```
   - If you’re working on GitHub’s web interface, create a new branch from the branch dropdown menu.

### 4. **Make Your Changes**
   - Edit the file(s) in the branch you just created.
   - Be as clear and precise as possible in your edits.

### 5. **Commit the Changes**
   - After making your edits, commit them with a detailed message explaining why the changes are being recommended:
     ```bash
     git add .
     git commit -m "Recommended changes: [Brief description]"
     ```
   - On GitHub, fill out the commit message and commit directly to the new branch.

### 6. **Push Your Branch (If Working Locally)**
   - Push your changes to your forked repository on GitHub:
     ```bash
     git push origin recommended-changes
     ```

### 7. **Create a Pull Request (PR)**
   - Go to your forked repository on GitHub.
   - You’ll see a prompt to compare and create a pull request for the new branch. Click "Compare & pull request."
   - In the PR description, explain the context of your changes, why they’re necessary, and any potential impact.

### 8. **Request Feedback**
   - Add relevant collaborators or maintainers as reviewers to the PR.
   - Politely ask for feedback and discuss your recommendations.

### 9. **Be Open to Revisions**
   - Be prepared to discuss your changes and make revisions based on feedback.
   - Use GitHub’s PR comments feature to engage in discussions about the changes.

### 10. **Resolve Conflicts and Update**
   - If there are merge conflicts, resolve them by rebasing your branch or merging the latest changes from the main branch:
     ```bash
     git fetch origin
     git checkout main
     git merge origin/main
     git checkout recommended-changes
     git rebase main
     ```
   - Push the resolved changes back to your fork:
     ```bash
     git push origin recommended-changes --force
     ```

### 11. **Final Approval and Merge**
   - Once all discussions are resolved and the maintainers are satisfied, the PR will be approved and merged.
   - This will integrate your recommended changes into the main repository.

### 12. **Follow-Up**
   - After the merge, follow up to see how the changes are working out and if further adjustments are needed.
