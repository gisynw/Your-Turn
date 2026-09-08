# Random Student Picker

A simple, classroom-friendly random student picker that can be hosted for free with **GitHub Pages**.

## Features

- Randomly divides students into a chosen number of discussion groups

- Randomly selects one student
- Option to avoid selecting the same student twice in a row
- Tracks how many times each student has been selected
- Summary table with frequency bars
- Saves counts in the current browser using `localStorage`
- Reset button
- Works as a single static HTML file; no server is required

## Run locally

Open `index.html` in a web browser.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and `.nojekyll`.
3. Open the repository's **Settings**.
4. Go to **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select your main branch and the `/ (root)` folder.
7. Save. GitHub will provide a public Pages URL.

## Edit the roster

Open `index.html` and find:

```js
const students = [
  ...
];
```

Add, remove, or rename students there.

## Privacy note

This version includes student names only. It does not upload or transmit data. Selection counts are stored locally in the browser.

## Group discussion mode

Enter the number of groups (for example, `4`) and click **Divide into Groups**. The roster is shuffled and distributed as evenly as possible among the requested groups.
