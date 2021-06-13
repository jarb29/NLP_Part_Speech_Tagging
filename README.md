Introduction
In this notebook, you'll use the Pomegranate library to build a hidden Markov model for part of speech tagging with a universal tagset. Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

Tasks
The notebook already contains some code to get you started. You only need to add some new functionality in the areas indicated to complete the project; you will not need to modify the included code beyond what is requested. Sections that begin with 'IMPLEMENTATION' in the header indicate that you must provide code in the block that follows. Instructions will be provided for each section, and the specifics of the implementation are marked in the code block with a 'TODO' statement. Please be sure to read the instructions carefully!

NOTE: There is an optional warmup exercise to introduce the Pomegranate API included in the project files. Just launch the HMM warmup (optional).ipynb file first to get started there, then complete the hmm tagger.ipynb notebook. (Only the tagger will be submitted for review.)

You must complete sections 1 to 3 below to pass the project. Please note that section 4 is optional. It is provided as references and resources if you wish to further explore HMM taggers.

Review the provided interface to load and access the text corpus
For both Most Frequent Class (MFC) tagger and the HMM model we'll build, we need to estimate the frequency of tags & words from the frequency counts of observations in the training corpus.
Build a Most Frequent Class (MFC) tagger to use as a baseline
Implement Pair Counts and Most Frequent Class
Build an HMM Part of Speech tagger and compare to the MFC baseline
Implement Unigram Counts, Bigram Counts, Starting Counts, Ending Counts, and Basic HMM Tagger using the Pomegranate HMM library.
(Optional) Improve the HMM tagger
Getting Started
You can choose one of two ways to complete the project. The first method is to use the Workspace embedded in the classroom in the next lesson. The Workspace has already been configured with all the required project files for you to complete the project. Simply open the lesson, complete the sections indicated in the Jupyter notebook, and then click the "submit project" button.

NOTE: If you are prompted to select a kernel when you launch a notebook, choose the Python 3 kernel.

Alternatively, you can download a copy of the project materials and then run a Jupyter server locally on your machine. Select the appropriate link for your program below, then follow the instructions in the readme to set up and complete the project.

NOTE: These steps are not required if you are using the project Workspace.

AIND GitHub: here (Projects/4_HMM Tagger)
NLPND GitHub: here
Evaluation
Your project will be reviewed by a Udacity reviewer against the project rubric. Please review this rubric thoroughly and self-evaluate your project before submission. All criteria found in the rubric must meet specifications for you to pass.

Submission
Once you have completed all of the code implementations, you need to finalize your work by exporting the iPython Notebook as an HTML document. Before exporting the notebook to HTML, all of the code cells need to have been run so that reviewers can see the final implementation and output. You must then export the notebook by running the last cell in the notebook, or by using the menu above and navigating to File -> Download as -> HTML (.html) Your submissions should include both the HTML and ipynb files.

Add the "hmm tagger.ipynb" and "hmm tagger.html" files to a zip archive and submit it with the button below. (NOTE: If you complete the project in the workspace, then you can submit directly using the "submit" button in the workspace.)

