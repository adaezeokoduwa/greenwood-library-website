# Capstone Project: Enhancing the Greenwood Community Library Website

## 📚 Project Overview

This project simulates a team collaboration to enhance the **Greenwood Community Library** website. The goal is to make the site more engaging by adding a new **"Book Reviews"** section and updating the **"Events"** page to show upcoming community events.

The existing pages include:
- Home
- About Us
- Events
- Contact Us

This capstone project involves simulating the contributions of two team members:
- **Morgan**: Adds the *Book Reviews* section.
- **Jamie**: Updates the *Events* page.

---

## 🎯 Objectives

- Learn how to clone a GitHub repository.
- Practice branching, staging, committing, and pushing changes using Git.
- Experience real-world collaboration by creating and merging pull requests (PRs).

---

## ⚙️ Setup Instructions

### 1. Create a GitHub Repository
- Go to [GitHub](https://github.com) and created a new repository named: greenwood-library-website
- Initialize it with a `README.md` file.
- Clone the repository to the local machine: Vscode
```bash
git clone https://github.com/your-username/greenwood-library-website.git
cd greenwood-library-website
```
## 🧱 Initial Project Structure

### 2. Basic Web Pages Added

In the **main** branch:

1. Opened the project in **Visual Studio Code**.
2. Created the following HTML files:
   - `home.html`
   - `about_us.html`
   - `events.html`
   - `contact_us.html`
3. Added ramdon text to each files

### 3. Commit Initial Files and Push

After saving all the files, I opened the terminal and ran the following Git commands:

```bash
git add .
git commit -m "Add base HTML pages"
git push -u origin main
```

# 📚 Morgan's Task: Adding Book Reviews Section

## ✅ Step 1: Created and Switch to a New Branch
1. Created a folder on my local terminal
2. Opened it on Vscode
3. Clone the repository
   ```bash
git clone https://github.com/your-username/greenwood-library-website.git
```
4. Open the terminal and run the following command to create a new branch and switch to it:

```bash
git checkout -b add-book-reviews
```
5. Created a new HTML file named book_reviews.html in your project directory and added randome text

## 💾 Step 2: Commit and Push Changes
Run the following commands to stage the new file, commit the changes, and push the new branch to GitHub:

```
git add book_reviews.html
git commit -m "Add book reviews section"
git push origin add-book-reviews
```

## 🔁 Step 3: Create a Pull Request (PR)

1. Went back to the GitHub repository on the web.
2. Located the `add-book-reviews` branch.
3. Clicked **Compare & pull request** next to the branch name.
4. Entered a **title** and a **description** for the pull request explaining the changes made.
5. Clicked **Create pull request** to submit it for review.
6. Once the changes are approved, clicked **Merge pull request**.
7. Finally, click **Confirm merge** to integrate the branch into the main codebase.


# 🗓️ Jamie's Task: Updating Events Page

## ✅ Step 1: Create and Switch to a New Branch
1. Created a folder on my local terminal
2. Opened it on Vscode
3. Clone the repository
   ```bash
git clone https://github.com/your-username/greenwood-library-website.git
```
4. Open the terminal and run the following command to create a new branch and switch to it:

```bash
git checkout -b update-events-page
```
5. Modify events.html, Edit events.html with random updated event content

## 💾 Step 2: Commit and Push Changes
Run the following commands to stage the new file, commit the changes, and push the new branch to GitHub:

```
git add book_reviews.html
git commit -m "Update events page with upcoming community events"
git push -u origin

## 🔁 Step 3: Create a Pull Request (PR)

1. Went back to the GitHub repository on the web.
2. Located the `add-book-reviews` branch.
3. Clicked **Compare & pull request** next to the branch name.
4. Entered a **title** and a **description** for the pull request explaining the changes made.
5. Clicked **Create pull request** to submit it for review.
6. Once the changes are approved, clicked **Merge pull request**.
7. Finally, click **Confirm merge** to integrate the branch into the main codebase.



