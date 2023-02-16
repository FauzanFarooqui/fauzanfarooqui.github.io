---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Here is an outline of my projects, which are primarily NLP/Deep Learning-focused or university course projects.

## Natural Language Processing
- **Statistical Machine Translation** [[PPT]](https://docs.google.com/presentation/d/1-58IoGHbNI8Ji9Tqlyz_v6sYBe4C2gTJr_5YjeeAV4A/edit?usp=sharing) \
    _Language Technologies Resouce Center, International Institute of Information Technology - Hyderabad_ \
    _June '22_ \
    This project was done and presented at [IASNLP'22](https://ltrc.iiit.ac.in/iasnlp2022/) - IIIT-H's Advanced Summer School on Natural Language Processing. 
    - Investigated the effects of tuning English to Hindi, Telugu, Tamil SMT models on different evaluation metrics (BLEU, chrF, TER, etc).

- **Open Information Extraction** (research work in-progress) \
    _VNIT, Nagpur_ \
    _July - December '22_
    - Aimed at using improved embedding techniques to effectively perform the NLP task of extracting structured triples from natural language sentences.
    - Working towards a publication to share results. This work was supervised by Prof. Dr. Mansi Radke.

The following NLP projects were done as part of the Natural Language Processing team at [IvLabs](https://www.ivlabs.in/), VNIT's AI & Robotics Lab. 

- **Sentiment Analysis (Text Classification)** [[GitHub]](https://github.com/IvLabs/Natural-Language-Processing/tree/master/text_classification) \
    _January '22_
    - Aimed at classifying the polarity of a topic.
    - Read papers on different architectures for Sentiment Analysis and Text Classification.
    - Benchmarked the following landmark architectures in PyTorch on the IMDb Movie Reviews dataset.
        - LSTM - Test Accuracy: 87.62%
        - FastText - Test Accuracy: 86.28%
        - BERT - Test Accuracy: 91.44%

- **Neural Machine Translation** [[Github]](https://github.com/IvLabs/Natural-Language-Processing/tree/master/neural_machine_translation) \
    _December '21_
    - Read papers on novel architectures for translation among languages.
    - Implemented landmark architectures in PyTorch using the Multi30k Dataset for German-English.
        - [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - BLEU Score: 37.5 
        - [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473) - BLEU Score: 31
        - [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215) - BLEU Score: 20

- **Text Generation** [[GitHub]](https://github.com/IvLabs/Natural-Language-Processing/tree/master/char_rnns) \
    _June '21_
    - Generated dinosaur names by building a character-level Language Model.
    - Compared the results of different sequence models such as Vanilla RNN, LSTM and GRU, in PyTorch.

## Course Projects
The following were done as assignments for various Computer Science undergraduate courses at VNIT.

- **Traveling Salesman Problem Solver using A* Search** [[GitHub]](https://github.com/FauzanFarooqui/TSP-solver) \
    _Artificial Intelligence_ \
    _October '22_
    - Implemented the A* search algorithm to solve the TSP, using the minimum spanning tree heuristic function.

- **N-tile Puzzle Solver using Bidirectional Search** [[GitHub]](https://github.com/FauzanFarooqui/n-tile-Puzzle-Solver) \
    _Artificial Intelligence_ \
    _August '22_
    - Implemented the bidirectional search algorithm to solve the puzzle, using breadth-first search in both directions.

- **Linux Command Shell using Multi-threading** [[GitHub]](https://github.com/FauzanFarooqui/Linux-Shell) \
    _Operating Systems_ \
    _September '21_
    - Implemented a basic Linux shell using multithreading in C POSIX.
    - Built to handle multiple serial/parallel commands, output redirection, change of directory and signal interrupts.

- **Weather Tracking Network using AVL BST** [[GitHub]](https://github.com/FauzanFarooqui/Data-Structures-Project---Weather-Data-Sensing-Network) \
    _Data Structures_ \
    _April '21_
    - Developed a weather data repository that keeps a record of data collected from a (hypothetical) sensor grid spanning a city, and tracks all the sensors.
    - Implemented AVL Binary Search Trees for the Weather Data and Sensor Network data structures, with various operations for interaction and management.

- **Heap Memory Manager** [[GitHub]](https://github.com/FauzanFarooqui/Heap-Memory-Management) \
    _Concepts in Programming Languages_ \
    _February '21_
    - Implemented the malloc and free functions in C, on a heap, using the first-fit allocation strategy.

## Miscellaneous
- **Handwritten Digits Recognizer** [[GitHub]](https://github.com/FauzanFarooqui/Handwritten-Digits-Classifier) \
    _December '20_
    - Aimed at building a handwritten digits classifier, trained on the MNIST dataset.
    - Implemented the LeNet-5 architecture in PyTorch.
- **Personal Finance Tracker in Google Sheets / MS Excel** \
    _July '21_
    - Made a complete functional custom workbook to track expenses, income and upcoming expenses across months throughout a year, with category-wise budgets and a consolidated dashboard of the overall health of your wealth. 
    - Used complex and important sheets' functionalities like Macros, App Scripts, cross-sheet queries, pivot tables, conditional formatting, VLookups, charts, formulae, etc.
    - With the above know-how, also built:
        - A Courses-and-GPA tracking sheet for university students that can be used to visualize performance, record test marks, and calculate elective credits and GPAs to plan into the future.
        - A Time Tracker to track time spent throughout the day. Flexibly records time spent by category and visualizes how useful which parts of the day were, hours of productivity (or otherwise, like unavoidable work) for the day and week, etc. 
    - PS: All three of them are highly personalized to my needs/schedule, the customization has been necessary to make these meta-trackers actually useful. Thus, I highly encourage everyone to learn basic Excel/Sheets (you can never get enough!) and you had be surprised by how useful you can get it to be.
