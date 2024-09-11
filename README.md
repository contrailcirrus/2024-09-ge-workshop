# Pycontrails workshop @ GE LEAD symposium

Workshop materials are organized in notebooks designed for use in [Colab](https://colab.research.google.com/). To open a notebook in Colab, navigate to the notebook on Github and click the "Open in Colab" badge. 

Experience indicates that trying to run notebooks locally during workshops results in using most of the workshop time troubleshooting issues with environment setup--so, while notebooks can in principle run locally, we strongly suggest using Colab during the workshop. If you want to re-use materials from the notebooks after the workshop, please feel free to reach out if you have questions about setting up a local environment.

## Pre-workshop setup

- Sign up for a [Google Cloud Platform](https://cloud.google.com/?hl=en) account if you do not already have one. Unfortunately, this requires a credit card even if you only plan to use the $300 of free credits given to new users.

- Send the email used to create the GCP account to [tristan.abbott@breakthroughenergy.org](mailto:tristan.abbott@breakthroughenergy.org?subject=GE%20workshop%20setup) so you can be given access to resources required for the workshop.

- Sign into your GCP account and go to the [Project Selector](https://console.cloud.google.com/projectselector2). Select the project you want to use for the workshop (or create a new project), and note its project ID.

- Check that you can authenticate with your GCP account in Colab by opening and running [test-setup.ipynb](https://colab.research.google.com/github/contrailcirrus/2024-09-ge-workshop/blob/main/test-setup.ipynb) in Colab. You will need to paste the project ID you noted in the previous step into one of the cells before running. If successful, you should end with a plot of low and high temperatures in Schenectady.

## Outline (WIP)