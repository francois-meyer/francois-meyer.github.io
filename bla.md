---
layout: page
title: Capstone Project
permalink: /bla/
---

<!-- <<!-- h2>Demo Information</h2>

* STEP 1: Download your demo submission from Amathuba.
* STEP 2: Download the txt files for training and tokenizing from [here](https://drive.google.com/file/d/1xJaxLAX08LfskKvcKVW78fzRRZWddc2c/view).
* STEP 3: Start up your IBPE website/program (using the Amathuba files) on your laptop.
* STEP 4: The client will operate the IBPE tokenizer, on your machine, testing the requirements one at a time.

Please test STEPS 1--3 at home, so we don't run into any delays during the demo. If the file size constraints of Amathuba prevented you from submitting your entire program (e.g. large libraries and dependencies), just explain that your demo uses additional code bases (not code you wrote yourself) besides your Amathuba files. -->

	
<h2>Bloom Taxonomy Annotator (BLA)</h2>


The aim of this project is to develop a web-based interface for automatically labelling test questions according to Bloom’s Taxonomy. Bloom’s Taxonomy is a framework commonly used in education to classify learning objectives and questions by cognitive complexity. It consists of six levels, ranging from simple recall of facts (Remember) to more complex tasks like evaluating arguments (Evaluate) or designing new ideas (Create). Labelling questions according to these levels can help lecturers estimate the level of difficulty of an exam that they are setting.

In this project, students will build a web interface that allows users to submit a test or exam paper – either by uploading a file or entering questions manually. The system will then label each question with the most appropriate Bloom category using a pretrained language model fine-tuned for this task (e.g. [uw-vta/bloominzer-0.1](https://huggingface.co/uw-vta/bloominzer-0.1). The labelled questions will be displayed in an interface, with the option for users to edit the labels and export the final result. This project will give students practical experience with language models, text classification, and user interface development.


<h2>Resources</h2>

* [Bloom's taxonomy](https://tips.uark.edu/using-blooms-taxonomy/)
* [Week 1 slides: Introducing the project](https://drive.google.com/file/d/171zX20xmgomXx_q7kFEXPPeFczeJ6Fdp/view?usp=sharing)
* [Bloominizer on Huggingface](https://huggingface.co/uw-vta/bloominzer-0.1).
* [Huggingface tutorial](https://huggingface.co/docs/transformers/en/tasks/sequence_classification). You don't have to train or finetune a model yourself, so you can skip to [Inference](https://huggingface.co/docs/transformers/en/tasks/sequence_classification#inference). Check out other resource like [this](https://huggingface.co/docs/transformers/main/en/task_summary#text-classification) and [this](https://github.com/huggingface/transformers/issues/6849) to extract more details about model predictions (such as probabilities for each Bloom class, as opposed to only returning the 1 predicted class.)

<h2>Contact</h2>

* Supervisor/Client: Francois Meyer \
  Email: francois dot meyer at uct dot ac dot za \
  Office: Room 316, Computer Science Building	

* Tutor: Conor Mckeag \
  Email: MCKCON007 at myuct dot ac dot za
