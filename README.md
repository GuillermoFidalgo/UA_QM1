# Quantum Mechanic Notes for PH 541

[![My LaTeX CI](https://github.com/GuillermoFidalgo/UA_QM1/actions/workflows/ci.yaml/badge.svg)](https://github.com/GuillermoFidalgo/UA_QM1/actions/workflows/ci.yaml)

## Pre-commit ci
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/GuillermoFidalgo/UA_QM1/main.svg)](https://results.pre-commit.ci/latest/github/GuillermoFidalgo/UA_QM1/main)

## Contribution

- If you wish to contribute just follow the standard fork and push workflow.
- If you don't have a working latex installation to compile the documents you could use the docker image from Texlive.

```bash
docker pull texlive/texlive # Warning: Over 5GB in size!!
```

To contribute just ignore the `HW1/` folder, the bulk of the work is to be done in the `Notes/` directory where you will find the following structure

```
Notes
├── Beamer-Template.tex
├── HW_Template.tex
├── Images
│   └── UA_logo.jpg
├── Lecture_notes
│   └── Ch1.tex
└── main.tex
```

### *Interested in contributing but not sure how to get setup?*
Just contact me, I'll get you setup with whichever configuration you are most comfortable with!

I would say the easiest setup involves using docker and VSCode with the `Latex Workshop` extension. A little configuration tweaks and bingo!

## FAQs

- Can I use Overleaf?

  Sure, I don't see why not. However, unless you have premium features of Overleaf, you won't be able to sync to Github and contribute the regular way.
- What's all this pre-commit and ci stuff?

  No need to worry about it. I have added these features to automatically check for typos and help me develop the project. You don't have to do anything other than just make PR to the main branch.
