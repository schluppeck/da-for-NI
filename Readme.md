# Notes for C84DAN - Data analysis for Neuroimaging

## Summary

These are the materials for a *data analysis for neuroimaging* module.

In the class, we acquire functional MRI data sets (in small groups) and use a combination of tools to analyse the data.

The **assignement** is a short report (250w abstract, main doc max 1500w; max 5 figures) that summarise the results from the analysis. Effort and attention to detail should be weighted towards a clearly written abstract (250w), methods, results and discussions. Only a brief Introduction is required.

- 10 credits, seven 2h sessions.
- first run: Feb 2017

## Data acquired in the scanner

1. T1w-MPRAGE: to illustrate detailed (1mm isotropic) anatomy
2. field map: to show that B0 can be measured
3. fMRI experiment (block): TR 2s, TE 40ms, 240s
4. fMRI experiment (event-related): same scanning parameters.
5. [additional, if time permits] EPI data (test): 5 echoes at different TEs to illustrate T2* decay


## Materials for stimuli:

We will provide the stimulus code (written in Matlab / MGL) in line with what happened in - [Learning Matlab / C84NIM](https://github.com/schluppeck/learningMatlab) - a pre-requisite for this course.

We'll run a "Faces versus houses / scenes localiser, as this works well and is a very robust experiment.

- Faces download:
http://wiki.cnbc.cmu.edu/images/multiracial.zip

>Stimulus images courtesy of Michael J. Tarr, Center for the Neural Basis of Cognition and Department of Psychology, Carnegie Mellon University, http://www.tarrlab.org/. Funding provided by NSF award 0339122.


- Scenes download: http://timbrady.org/stimuli/Scenes.zip

>Scene stimuli from: Konkle, T.*, Brady, T. F.*, Alvarez, G.A. and Oliva, A. (2010). Scene memory is more detailed than you think: the role of categories in visual long-term memory. Psychological Science, 21(11), 1551-1556.
