
# Troubleshooting — Cyber Range and VS Code

These instructions apply to the **assigned cyber range machine**, not to a personal Google Colab environment.

## 1. I Don't Know Where to Start

Open the **Getting Started HTML guide on your cyber range desktop**. Then double-click the **course shortcut** to launch VS Code.

## 2. The Course Shortcut Does Not Open VS Code

- Wait briefly for the cyber range desktop to finish loading.
- Try the course shortcut once more.
- Check whether VS Code opened behind another window.
- If the shortcut is missing or broken, contact the instructor or cyber range administrator. Do not attempt to reinstall or reconfigure the environment without authorization.

## 3. I Cannot Find a Module

In VS Code, open the **Explorer** panel (View → Explorer) and look for the module folders. If the course workspace is not visible, reopen it using the desktop shortcut. Contact the instructor if files are missing.

## 4. I Cannot Make a Copy

Right-click the `.ipynb` file in VS Code Explorer and choose **Copy**. Paste it into your instructor-designated personal work folder and rename it. If the folder is unavailable or read-only, ask your instructor where personal work should be stored. **Do not modify the shared original.**

## 5. The Notebook Will Not Run

- Verify that you opened **your copied `.ipynb` file**.
- Confirm the notebook is using the course-provided Python kernel/environment.
- Run prerequisite setup cells before later cells.
- Read the full error message.
- If the course kernel is missing, contact your instructor rather than installing a new environment yourself.

## 6. Python Kernel Is Not Available

Use **Select Kernel** in the notebook toolbar and choose the environment provided for the course. If no suitable kernel appears, notify the instructor or cyber range administrator.

## 7. `NameError` or Missing Variable

An earlier cell may not have run, or a variable may be misspelled. Run required earlier cells in order and check variable names.

## 8. `ModuleNotFoundError` or Missing Package

The cyber range should contain the course's required tools. Check whether the notebook includes a setup step. If the package is still unavailable, contact your instructor. Do not install arbitrary packages or change system configuration without authorization.

## 9. Code Runs Slowly or Freezes

Some model experiments take time. Check the cell's status and avoid starting duplicate runs. If the environment becomes unresponsive, note the task and contact the instructor before restarting or changing system settings.

## 10. My Results Differ from an Example

Random seeds, dataset splits, model settings, and package versions can affect outputs. Verify the requested parameters and explain your observed results instead of replacing them with expected values.

## 11. I Lost My Work or the Cyber Range Session Ended

Check your designated personal working folder and any approved backup location. The persistence of files between sessions depends on the cyber range configuration; ask your instructor if unsure. Do not assume that desktop or temporary files will be retained.

## 12. I Accidentally Edited the Original Notebook

Stop editing the original. Save any needed work to an approved personal copy, then inform the instructor if the original course file may have changed. Do not overwrite shared materials.

## 13. I Cannot Submit My Notebook

Confirm that your file is saved as `.ipynb`, uses the required naming convention, and is in your personal folder. Ask the instructor for the approved submission location or transfer method. **Do not post submissions publicly on GitHub.**

## When Requesting Help

Provide your module number, task, error message, and steps attempted. Never share passwords, tokens, or private credentials.

[Getting Started](GETTING_STARTED.md) | [Submission Guidelines](SUBMISSION_GUIDELINES.md) | [Course Home](README.md)

