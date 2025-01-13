---
layout: page
title: Text 2 SQL using Llama
description: A text to SQL conversion tool using Llama and SFT
img: assets/img/text2sql/thumbnail.jpg
importance: 2
category: work
giscus_comments: true
---

## About

Text-to-SQL is a challenging task that involves converting natural language questions into SQL queries. This project aims to build a text-to-SQL conversion tool using the [Meta-llama-7B](https://huggingface.co/meta-llama/Llama-2-7b) model with supervised fine-tuning using sql-create-context dataset [b-mc2](https://huggingface.co/datasets/b-mc2/sql-create-context).The project involves training the Llama model using SFT and evaluating its performance on a test set of text-to-SQL examples.

## Background
Text-to-SQL is a challenging task that involves converting natural language questions into SQL queries. 
Text-to-SQL is a challenging task that involves converting natural language questions into SQL queries. 

### Large Language Models


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/Transformers.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Large Language Models are advanced natural language processing models characterized by enormous size, typically containing tens or hundreds of billions of parameters. These models are trained on large-scale datasets using unsupervised learning techniques and have been shown to achieve state-of-the-art performance on a wide range of natural language processing tasks.
</div>

### How LLM's are Trained

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/training.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    write about pre-training , SFT and RLHF
</div>

### Difference between SFT and RLHF

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/rlhf.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    write about pre-training , SFT and RLHF
</div>


### Different ways to fine-tune LLM's

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/training_methods.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    write about pre-training , SFT and RLHF
</div>

## Methodology

Fine-tuning enormous language models is prohibitively expensive in terms of the hardware required and the storage/switching cost for hosting independent instances for different tasks. In the full fine-tuning of LLMs, there is a risk of catastrophic forgetting, where previously acquired knowledge from pretraining is lost.

### PEFT
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/peft.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    PEFT is designed to fine-tune models while minimizing the need for extensive resources and cost. PEFT is a great choice when dealing with domain-specific tasks that necessitate model adaptation. Using PEFT we can balance retaining valuable knowledge from the pre-trained model and adapting it effectively to the target task with fewer parameters. 
</div>

### LORA
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/lora.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    PEFT is designed to fine-tune models while minimizing the need for extensive resources and cost. PEFT is a great choice when dealing with domain-specific tasks that necessitate model adaptation. Using PEFT we can balance retaining valuable knowledge from the pre-trained model and adapting it effectively to the target task with fewer parameters. 
</div>

### Results

Here are some results tested on blind dataset

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/result1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/result2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/result3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/text2sql/result4.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Ways to improve

- We can try different modles with more parameters like Llama-70, GPT-4 etc

- Better prompting can like explaining context of variables and tables can be used to improve the performance.

- Use data centric approach with more SQL QA datasets and instruction based datasets.

- RLHF can be incorporated by ranking the output and using human feedback to improve the model.

- Customizing loss functions to penalize for retrieving the correct query, which will help in interpretability and explainability of the model.

- Pre-checking the validity of questions can help in reducing the errors in the output.
