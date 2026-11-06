

# Troubleshooting — Securing AI

This guide addresses common problems encountered while using Google Colab and completing the Securing AI notebooks.

---

## 1. A Code Cell Will Not Run

Possible causes:

- The runtime is disconnected.
- A previous setup cell was not executed.
- A required variable has not been defined.
- A Python package is missing.
- The cell contains an incomplete student task.

### Recommended Steps

1. Confirm that the runtime is connected.
2. Run the notebook's setup and import cells.
3. Read the error message carefully.
4. Check that all required variables exist.
5. Verify that the task has been completed.

If necessary, select **Runtime → Restart session** and execute the required cells again.

---

## 2. NameError: Variable Is Not Defined

A `NameError` often means that a variable has not been created in the current session.

### Solution

Run the earlier cell that defines the variable.

Check for spelling mistakes and differences in capitalization.

Do not rename variables used by later cells unless the instructions require it.

---

## 3. ModuleNotFoundError

This error indicates that Python cannot find a required library.

### Solution

Run any installation or setup cells provided in the notebook.

If the notebook requires a package that is not installed, review the module instructions before installing it.

Avoid changing package versions unless instructed.

---

## 4. The Notebook Is Taking Too Long

Some machine learning experiments require additional processing time.

### Solution

- Wait for the current cell to finish.
- Avoid running the same cell repeatedly.
- Check whether the runtime is still connected.
- Review the activity instructions for expected runtime behavior.

If an experiment appears stuck, record the cell and contact your instructor before changing the required experiment.

---

## 5. My Results Are Different from the Example

Machine learning experiments may produce different results because of:

- Random initialization.
- Dataset splitting.
- Model training behavior.
- Software versions.
- Parameter changes.

### Solution

Check the random seed and experiment parameters.

Confirm that you followed the instructions.

When asked to analyze results, explain the values you actually observed rather than replacing them with expected values.

---

## 6. My Runtime Disconnected

Google Colab runtimes may disconnect after inactivity or because of resource limitations.

### Solution

1. Reconnect to the runtime.
2. Run the setup cells.
3. Restore any required data or files.
4. Execute the necessary experiment cells again.

Variables stored only in runtime memory may be lost after a reset.

---

## 7. I Cannot Edit the Notebook

You may have opened the original notebook directly from GitHub.

### Solution

Select:

**File → Save a copy in Drive**

Edit the personal copy instead of the repository version.

---

## 8. I Cannot Find My Notebook

Open Google Drive and look for the notebook in your Colab notebooks folder or use Drive search.

If you downloaded a copy, check your computer's Downloads folder.

---

## 9. I Cannot Open the Notebook from GitHub

Try the following:

1. Open the module folder in GitHub.
2. Select the `.ipynb` file.
3. Download the notebook.
4. Visit https://colab.research.google.com/
5. Select **File → Upload notebook**.
6. Upload the downloaded `.ipynb` file.

---

## 10. I Accidentally Changed Important Code

If you have a saved copy, use it to restore the affected code.

You may also download a fresh copy of the student notebook from GitHub and compare the original instructions with your work.

Do not replace your entire completed assignment unless necessary.

---

## 11. My Notebook Contains an Error During Submission

If your notebook contains an unresolved error:

- Record the error message.
- Explain what you attempted.
- Preserve your completed work.
- Contact your instructor for guidance.

An unresolved error does not automatically mean that every part of the assignment is incorrect.

---

## 12. I Need Additional Assistance

When requesting help, provide:

- The module number.
- The task or section number.
- The error message.
- The steps you attempted.
- A description of the expected behavior.

Do not share passwords, API keys, access tokens, or other sensitive credentials.

---

[Return to Course Home](README.md) |
[Getting Started](GETTING_STARTED.md)
