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
* B.S. in Mechanical Engineering, Missouri University of Science & Technology, 2011
* M.A. in Applied Linguistics, Dallas International University, 2015

Work experience
======
* 2021-Present: Founder and Executive Director
  * Intek Solutions
  * Registered business in Indonesia, developed business systems, hired and managed team of 7 employees
  * Managed cross-functional teams to define, design, and ship new features
  * Developed and maintained multiple android apps, using Java and the Android SDK

* 2019-Present: Language Development Specialist
  * 
  * Helped develop a pathway to developing Human Language Technology to promote human flourishing in low-resource language communities
  * Developed mobile crowdsourced dataset creation solution for low-resource languages in Indonesia
  * Helped develop monitoring and evaluation for the HLT competency

* 2014-2018: Translation Specialist
  * DLPI
  * Language and culture learning
 
* January 2012 - May 2014: Mechanical Engineer
  * Roeslein and Associates
  * Selected and acquired factory support equipment such as pumps, cooling towers, compressors, etc.
  * Sized and purchased pipe and hardware for factory installs
  * Oversaw onsite installations 

Projects
======
* ikata - <i>Crowdsourced Android app to create language datasets in low-resource languages</i>
  * Simple UI
  * Users are paid micropayments to contribute words and sentences in their minority language
  * Scoring system and leaderboard to drive user engagement
  * Backend code and user feedback utilized for quality control of crowd-sourced data
  * Backend: Django, Mysql, Firebase Auth, Firebase Realtime, Firebase Storage, Firebase Messaging
  * Implemented Multinomial Naive Bayes to identify language of contribution
  * Implemented spellcheck with Jaro-Winkler similarity to normalize non-standard spelling
  * Implemented Prompt set to collect labeled data for Domain Classification

* Alas Dictionary App - <i>Android dictionary app for the Alas language in Indonesia</i>
  * Adapted Udemy tutorial to fit the local context
  * Developed Alas-Indonesian-English dictionary using available language data
  * Includes features such as autocomplete of search term, user recommendations and corrections, search history, first app ever offered with Alas interface

* Apertium Alas Module - <i>Creation of Alas, Alas-Indonesian, and Alas-Malay modules in Apertium rule-based machine translation platform</i>
  * Created morphological generator and analyzer using Finite-State Morphology 
  * Worked with another computer scientist to update existing Indonesian and Malay modules to better match the Alas module
  * One of the first attempts to use the newer lexd lexicon compiler to compile bilingual dictionaries in Apertium

Skills
======
* Android Studio
  * Android Native development using Java
* Git
* Firebase
  * Firebase Auth
  * Realtime Database
  * Firestore
  * Cloud messaging
* MySql
* Python 
  * Pandas
  * Numpy
  * Scikit-learn
  * NLTK)
* Django
* Natural Language Processing
  * Especially in low resource languages
* Familiarity with agile development methodologies

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards
======
* Chancellor’s Scholarship - Missouri S&T
* Outstanding Academic Achievement Award 2008-2009 - Missouri S&T
* Eagle scout

