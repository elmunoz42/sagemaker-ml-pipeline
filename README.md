# Fine Tuning Lab - From ML Engineer Associate Course

## Train a Model with Amazon SageMaker  
**SPL-TF-300-MLMLMD-1 - Version 1.0.5**  
© 2025 Amazon Web Services, Inc. or its affiliates. All rights reserved.  
This work may not be reproduced or redistributed, in whole or in part, without prior written permission from Amazon Web Services, Inc. Commercial copying, lending, or selling is prohibited. All trademarks are the property of their owners.

> **Note:** Do not include any personal, identifying, or confidential information into the lab environment. Information entered may be visible to others.  
> **Questions or feedback?** Contact us at AWS Training and Certification.

---

## Lab Overview

AnyCompany Consulting has received data from a nonprofit advocacy group and prepared the dataset for training. As the data scientist, your task is to train a machine learning (ML) model and evaluate the results.

The label feature is a binary classification (less than \$50,000 or not), so you will:

- Use SageMaker’s built-in **XGBoost** algorithm.
- Evaluate prediction efficiency.
- Explore a custom scenario using XGBoost in **script mode** for advanced features like **k-fold cross-validation**.

---

## Objectives

By the end of this lab, you should be able to:

- Train a model using built-in SageMaker algorithms.
- Write custom training and inference code using ML frameworks maintained by AWS.
- Import custom libraries and dependencies.
- Set up a Hyperparameter Tuning Job in SageMaker.

---

## Icon Key

- ⚠️ **Caution:** Important info that may require repeating steps if missed.  
- ❗ **Warning:** Irreversible actions or critical configuration steps.  
- 📘 **Learn More:** Additional resources.  
- 💡 **Note:** Tips or guidance.  
- ✅ **Task Complete:** Summary or conclusion of a lab step.

---

## Start Lab

To launch the lab:

1. At the top of the page, choose **Start Lab**.  
   ⚠️ *Wait for AWS services to be ready before continuing.*
2. Choose **Open Console**.  
   You’ll be signed in automatically to the AWS Management Console in a new browser tab.  
   ❗ *Do not change the Region unless instructed.*

---

## Common Sign-In Errors

**Error:** Choosing Start Lab has no effect  
- Disable pop-up or script blockers.
- Add the lab domain to your allow list.
- Refresh the page and try again.

---

## Lab Environment

**Diagram Description:**  
An Amazon S3 bucket contains processed training data. A Jupyter notebook uses a training container image from an Amazon ECR repository. The notebook creates a model and stores it in another S3 bucket.

> AWS services not used in this lab may return errors if accessed.

---

## Task 1: Train a Model Using a Built-in Algorithm

### Task 1.1: Set Up the Environment
1. Copy the `SageMakerStudioUrl` from the instructions.
2. Open a new browser tab and paste the URL.
3. Press **Enter** to access JupyterLab.
   💡 *It may take 1–2 minutes to load.*

4. Clone the Git repository:
   - Choose the **Git** icon.
   - Select **Clone a Repository**.
   - Paste the `CloneUrlForRepo` and choose the suggested URL.
   - Choose **Clone**.

✅ *You have successfully launched SageMaker Studio and cloned the repository.*

### Task 1.2: Train the Model

1. Open `train_built_in.ipynb`.
2. Select kernel: **Python 3 (ipykernel)**.
   💡 *Kernel may take 1–2 minutes to load.*

3. Run each code cell:
   - Select the cell and press **Shift + Enter** or choose **Run**.

✅ *Notebook completed. Proceed to the next task.*

---

## Task 2: Train a Model Using a Custom Script (Script Mode)

1. Open `train_script_mode.ipynb`.
2. Select kernel: **Python 3 (ipykernel)**.
   💡 *Kernel may take 1–2 minutes to load.*

3. Run each code cell:
   - Select the cell and press **Shift + Enter** or choose **Run**.

✅ *Notebook completed. Lab is now finished.*

---

## Knowledge Check

This section helps reinforce your understanding of the lab content.

> **Why it matters:** Identifies areas for review and strengthens learning.

Choose **Launch Knowledge Check** to begin.

---

## Conclusion

You have successfully:

- Trained a model using built-in SageMaker algorithms.
- Written custom training and inference code.
- Imported custom libraries and dependencies.
- Set up a Hyperparameter Tuning Job in SageMaker.

---

## End Lab

1. Return to the AWS Management Console.
2. Choose **AWSLabsUser** > **Sign out**.
3. Choose **End Lab** and confirm.

---

## Additional Resources

- Amazon SageMaker Documentation
- AWS Training and Certification
- [Contact Form for Feedback](https://aws.amazon
