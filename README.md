# IFT6135 - Representation Learning - Course Notes

These are my personal notes from the course IFT6135 — Representation Learning — taught by Aaron Courville at MILA in Montreal, Quebec, during the Winter 2025 semester. The course ran from January to April, and it was a deep (pun intended) dive into the theory and practice of learning useful representations from data.

That said — fair warning! These notes are incomplete, sometimes messy (I often switch between French and English), and occasionally wrong. They reflect my own understanding of the material, and I’ve tried my best to make sense of complex ideas. Some parts were generated or cleaned up with the help of ChatGPT, others go slightly beyond what was taught in class. There are definitely missing citations, and I still plan to add more figures and references.

I’m sharing these in case they help others going through this intense (but rewarding!) course. If you spot errors, have suggestions, or want to expand a section, feel free to fork the repo and open a pull request. I’ll do my best to review changes promptly. If you do contribute, please don’t forget to add your name to the author list!

A sincere thank you to Professor Aaron Courville for his inspiring lectures, to the TAs for crafting such challenging and thought-provoking assignments, and to all the students — especially Thomas, Maël and Olivier — whose discussions, questions, and collaboration made the learning process far more engaging. It was a real privilege to be part of such a passionate and driven group.

And for those reading this outside the context of MILA — welcome! You’ll probably get the most out of these notes if you already have some background in math, computer science, and deep learning. A solid starting point is the Deep Learning book: https://www.deeplearningbook.org/.

Enjoy the ride — and good luck with your learning journey!

## Assessment

- **Assignments (75%):**  
  Three assignments at 25% each, consisting of:
  - **Theory (10%):** Solving theoretical problems.
  - **Practical (15%):** Implementation in PyTorch with code completion exercises.

- **Final Exam (25%):**
  - A three-hour final exam covering all course material and assignments.
  - An exam example is available online.
  - **Important Note:** The exam is challenging, so it is essential to maintain good performance on the assignments to compensate.

## Resources

- [Course Video 2024](https://sites.google.com/view/ift6135a-h2024/cours?authuser=0)
- [Course Slides](https://sites.google.com/view/ift6135a-h2025/cours?authuser=0)
- [Deep Learning](https://www.deeplearningbook.org/) by Ian Goodfellow, Yoshua Bengio, and Aaron Courville (available on Amazon or free online).
- [Course Overleaf](https://www.overleaf.com/project/659a4d39c93dd59cb90f2f7d)

## TODOs (Tasks and Improvements to Be Made)

This document contains several parts that are incomplete and/or need to be developed further. In addition, you will probably find many TODOs spread across the latex document.

### Section 1: Fundamental Concepts
- **Backpropagation:**  Provide a more detailed explanation of the backpropagation mechanism, its importance in training neural networks, and potentially compare it with other optimization methods.
- **Activation Functions:**  I think adding details about the activation functions used in modern architectures is needed.
- **Continual Learning:** I though adding a section about continual learning could be interesting.

### Section 2: Optimization
- **Weight Standardization:** Introduce the technique, its objective, and its benefits over traditional methods.
- **Learning Rate Decay:** I'm not sure where to place this concept and it would be helpful to develop a comprehensive explanation of the topic.

### Section 4: Convolutional Neural Networks (CNNs)
- **(De)convolution & Spatial Separable Convolution**

### Language Models (LLMs)
I think including some notes specific to the LLMs models could be interesting but I'm not sure where to place them.. This could include discussions about
- **Challenges**
- **Impact of Model Size on Performance**
- **Prompt Engineering:** Elaborate on techniques such as Chain of Thought (CoT) and Self Consistency, including examples on how to formulate effective prompts.

###  Section 8: Variational Autoencoders (VAEs)
- **Challenges and Techniques:** Aaron talked a lot about the different challenges of VAEs and techniques to adress them. It would be interesting to add more details about this.

###  Section 9, 10, 11
These sections are basically empty at the moment and need a lot of work.
