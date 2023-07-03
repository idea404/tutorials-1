# Community tutorials

This repository contains different tutorials submitted by community members. 

We encourage authors to keep their tutorials updated. 

## Tutorial requirements

- All tutorials must showcase how to develop applications on zkSync Era.
- Tutorials must take a neutral stance and refrain from promoting projects.
- Tutorials must be an original and NOT a work that was previously published.
- You must be the rightful intellectual property owner (author) of your submission.
- Tutorials can contain relevant external sources, only when referenced accordingly.
- Tutorials must have working code to support the tutorial.
- Tutorials must be provided following the [guidelines in this repository](#tutorial-guidelines).

## Tutorial guidelines

- Create a new folder inside `tutorials` with the name of your tutorial in *kebab-case*, e.g. `my-awesome-tutorial`.
- In this folder, create a `TUTORIAL.md`. The tutorial must follow this structure:
  - Title (Level 1 heading)
  - Introduction (Level 3 heading): explain what is going to be built in this tutorial.
  - Prerequisites (Level 2 heading): system and technical requirements. **Indicate the specific versions of packages and compilers used to build the project.**
  - Build time!: step-by-step details on how to build the project.
    - Step 1 — Doing the First Thing (Level 2 heading)
    - Step 2 — Doing the Next Thing (Level 2 heading)
    - Step n — Doing the Last Thing (Level 2 heading)
  - Conclusion (Level 2 heading): summarize what the reader has accomplished by following your tutorial
- Create a `code` folder with any code to support the tutorial.
- Create an `images` folder with any images to support the tutorial.

Use the [TUTORIAL_TEMPLATE](./tutorials/TUTORIAL_TEMPLATE.md) and [zksync-cli-quickstart tutorial](./tutorials/zksync-cli-quickstart/) as a reference.

## How to submit a tutorial

- Clone this repo.
- Create a new branch and [add your tutorial following the guidelines](#tutorial-guidelines).
- Make sure [your tutorial follows the requirements](#tutorial-requirements)
- Create a pull request.
