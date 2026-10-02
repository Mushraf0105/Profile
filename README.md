# Personal Webpage - Md Mushraf Ali

## Description
This project is a simple, responsive personal webpage created to showcase my profile, skills, hobbies, and contact information. It was built from scratch to practice basic HTML and CSS styling, responsive layout, and modern design aesthetics.

## Approach
- **Technologies Used:** HTML5 and CSS3.
- **Design System:** Implemented a modern dark-theme UI with a custom color palette (`#0f172a` for background, `#38bdf8` for accents). 
- **Typography & Icons:** Integrated Google Fonts (Inter) for clean typography and FontAwesome for intuitive icons.
- **Layout & Responsiveness:** Utilized CSS Flexbox and Grid to structure the sections (`About`, `Skills`, `Hobbies`, `Contact`) and ensure the layout adapts seamlessly to mobile devices. 
- **Animations:** Added subtle CSS `@keyframes` animations (fadeInUp/fadeInDown) and hover effects on cards and buttons to make the UI feel dynamic and engaging.

## Outcome
A fully functional, single-page personal portfolio that is visually appealing, easy to navigate, and highly responsive across all screen sizes.

## Deployment Configuration
To deploy this project using **GitHub Pages** (a free resource):
1. Initialize a Git repository in this folder and push it to a new public GitHub repository.
2. Navigate to the repository **Settings** on GitHub.
3. Scroll down to the **Pages** section on the left sidebar.
4. Under "Build and deployment", select **Deploy from a branch**.
5. Set the branch to `main` (or `master`) and the folder to `/(root)`.
6. Click **Save**. Your site will be published at `https://<your-username>.github.io/<repository-name>/`.

## Rollback Evidence / Version Control
This project relies on Git for version control. In the event of a critical issue or bug in a new deployment, rollback can be easily achieved by:
1. Identifying the last stable commit using `git log`.
2. Reverting to the previous stable state using `git revert <commit-hash>` (or `git reset --hard <commit-hash>` for local rollbacks).
3. Pushing the reverted changes to GitHub, which automatically updates the live deployment on GitHub Pages to the stable state.
