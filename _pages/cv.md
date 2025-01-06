---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in New Jersey Institute of Technology, Newark, NJ (2024)


Work experience
======
* 2020 -- 2024: Research Assistant in SABOC Lab
  * New Jersey Institute of Technology
  * Duties includes: 
    * Design and develop an Optimized Cluster-focused Combination annotator for annotating the EHRs text by referencing the user-defined interface terminology which achieve significant improvement on the text coverage and time efficiency by reducing the anno-tation execution time to second level compared to traditional annotation tools.
    * Developed Clinical & Medical Ontology Hierarchical Relation Predicting Pipeline with Large Language Models (LLM) which achieved a notable 96% macro accuracy with the preliminary research on varied LLM such as: Llama2-7b/2-13b, Openchat_3.5, Vi-cuna-13b-v1.5, Zephyr-7b-beta.
    * Extracted the medical relevant phrases from the open-sourced Cardiology patient notes and Covid-19 Radiology notes by using the self-designed concatenation and anchoring methodology.
    * Constructed the cardiology and Covid-19 interface ontology using protégé for annotation of the electronic health records. Experi-mented with the Mimic public source, EHR database.
    * Developed a hybrid (rule-base & machine learning--using spaCy/NLTK) Concept Review System to automatically validated the generated clinical & medical phrases from free text.

* 2020 -- 2024: Teaching Assistant / Lab Instructor 
  * New Jersey Institute of Technology
  * Duties included:
    * Tutored for CS331 Database Systems, CS634 Data Mining courses and CS413 Advanced Database.
    * Teaching for CS103 Business Analysis with Python and CS115 Introduction of Computer Science: C++ programming.


* 2023 Spring and Summer: Biomedical Informatics Co-op
  * Regeneron Pharmaceuticals
  * Duties included: 
    * Designed & Developed Name Entity Recognizer (NER) Plus Ontology Resolution Pipeline for identifying disease, cell and tissue related phrases from the large gene expression text dataset (Gene Expression Omnibus) and resolve such free-form phrases to exist-ing Disease, Cell and Tissue ontologies concepts by using Spark NLP Pre-trained Language Model on Databrick which achieved 95% F1 score outperformed among the other state-of-arts NLP models.
    * Designed & Developed Disease Abbreviation Identification Pipeline to detect and disambiguate the meaning of disease abbreviation in the GEO dataset.
    * Develop a novel annotation technique called “Cluster-Focused Combination,” an algorithm designed to enhance the breadth and depth of text annotations using user generated reference terminology.
    * Researched and trained on LDA Topic Modeling on classifying disease term in terms of Disease Ontology.
    * Researched and developed prompts for BioGPT Pre-trained Model for medical abbreviation detecting and ambiguating.
  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
