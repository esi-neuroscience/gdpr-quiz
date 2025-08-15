<!--
Copyright (c) 2025 Ernst Strüngmann Institute (ESI) for Neuroscience in Cooperation 
with Max Planck Society and Max Planck Institute for Human Development (MPIB)

SPDX-License-Identifier: CC-BY-SA-4.0
-->

# gdpr-quiz
A short interactive quiz covering what you really need to know about data 
protection for human subject research

## Setup

The quiz is built with [Quarto](https://quarto.org/) version 1.6+. Use the 
accompanying conda environment file to reproducibly build the slide deck: 


```shell
conda env create -f conda_env.yml
conda activate gdpr-quiz
quarto render gdpr_quiz.qmd
```

For working on the website

``` shell
quarto preview gdpr_quiz.qmd
```

Link to Quarto Quizdown
