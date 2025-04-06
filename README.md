Learning to use github using Intellipaat x IITM course for data science.
This repository demonstrates a git workflow architecture to be used Zendriix Softwares.

Branching Strategy:
main — Stable production branch. Only tagged releases go here.
develop — Integration branch for features & fixes.
release — Preparation branch for the monthly release.
feature/* — For developing new features.
hotfix/* — Critical fixes that may need quick deployment.

Workflow:
Developers work on feature/* branches.
Once a feature is ready, merge to develop.
On or around the 20th of each month, create a release branch from develop.
Test and finalize in release branch.
On the 25th of the month, merge release into main (production).
Merge release back into develop to sync.
