# Approximate NE Auto-Analyzer

This repository contains codes that conduct the auto-analysis on the approximation bounds of all algorithms in the literature. All codes are written in Mathematica notebook. 

## Requirements

Mathematica (pro or student version) should be installed. The version of Mathematica should be >= 12.0.0; we do not guarantee the compatibleness for other versions.

## Naming rules

All files have the following name structure: `[author initials]-[approximation bound].nb`. 
- If the approximation bound in decimal representation is $0.xxxx$, then in the filename it is written in form `0_xxxx`.

For example, the file `BBM-0_36.nb` implements the auto-analyzer of our revision of the $0.36$-approximation algorithm proposed by Bosse, Byrka, and Markakis.

## How to view/run the code

To view the code, open the `.nb` file with Mathematica. Then the Mathematica code is presented in the correct form. DO NOT open the code using other text editors, which may not present the code correctly.

Note that our codes also record the result of the whole evaluation. However, you can rerun the code on your own. To run the code, after opening the code, click Evaluation -> Evaluation Notebook. Then you will see the output in a few seconds (at most minutes).