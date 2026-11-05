# How to Update the Application SOP

This guide explains how to update the application's Standard Operating Procedure (SOP) using GitHub.

**Note:**
- Users without bypass permissions cannot commit directly to `main`. The **Commit changes** button will not be available.
- **Do not select "Create a new branch for this commit and start a pull request" when attempting to make changes from `main`.**
- Do not create any new branches for SOP updates.
- Always switch to the existing `edit-sop` branch and commit your changes directly to it.
- Create a Pull Request from the existing `edit-sop` branch into `main`.

**Important:** The `main` branch is protected. Users without bypass permissions cannot commit changes directly to `main`. You must switch to the existing `edit-sop` branch before making any changes.

## Step 1: Switch to the `edit-sop` Branch

1. Open the GitHub repository.
2. Click the branch selector (currently showing `main`).
3. Select the existing `edit-sop` branch.

> **Important:** Always switch to `edit-sop` before editing. Do not attempt to edit or commit changes directly to `main`.

## Step 2: Edit the SOP

1. Navigate to the SOP file.
2. Click the pencil icon (**Edit this file**).
3. Make the required changes.
4. Click **Commit changes...**.

## Step 3: Commit Your Changes

1. Enter a short description of your changes.
2. Ensure the changes are being committed to `edit-sop`.
3. Select **Commit directly to the edit-sop branch**.
4. Click **Commit changes** to save.

> **Important: Do not select the option to create a new branch and start a Pull Request.** You must commit directly to the existing `edit-sop` branch.

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
3. If changes are requested, update the SOP in the existing `edit-sop` branch and commit them. The changes will automatically appear in the existing PR. You do not need to create another PR.

Once approved and merged, your changes will be available in the `main` branch.
