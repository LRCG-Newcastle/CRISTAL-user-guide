# How to Update the Application SOP

This guide explains how to update the application's Standard Operating Procedure (SOP) using GitHub.

**Important:** The `main` branch is protected. If you try to commit changes directly to `main`, GitHub will not allow you to save them. Always use the `edit-sop` branch.

## Step 1: Switch to the `edit-sop` Branch

1. Open the GitHub repository.
2. Click the branch selector (currently showing `main`).
3. Select the `edit-sop` branch.

## Step 2: Edit the SOP

1. Click the pencil icon (**Edit this file**).
3. Make the required changes.
4. Click **Commit changes...**.

## Step 3: Commit Your Changes

1. Enter a short description of your changes.
2. Ensure the changes are being committed to `edit-sop`.
3. Click **Commit directly to the edit-sop branch** to save.

## Step 4: Create a Pull Request

1. Go to the **Pull requests** tab.
2. Click **New pull request**.
3. Select the following branches:
   - **Base:** `main`
   - **Compare:** `edit-sop`
4. Click **Create pull request**.
5. Enter a title and a brief description of your changes.
6. Click **Create pull request** to submit it.

## Step 5: Code Owner Review

1. The Code Owners will receive a notification to review your changes.
2. They will either approve the changes or request further modifications.
3. If changes are requested, update the SOP in the `edit-sop` branch and commit them. The changes will automatically appear in the existing PR.

Once approved and merged, your changes will be available in the `main` branch.
--

**Note:** Do not attempt to commit changes directly to `main`. The branch protection policy prevents direct commits, and GitHub will not allow you to save the changes. Always use `edit-sop` and submit your changes through a Pull Request.
