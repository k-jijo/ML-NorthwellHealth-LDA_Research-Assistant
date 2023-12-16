# ML-NorthwellHealth-LDA_Research-Assistant


## Introduction

## This research is in partnership with Northwell Health, New York State's largest healthcare provider and private employer. It invites engagement in the exploration of unstructured medical data, intending to reveal latent patterns and unveil critical insights that promise to enrich our understanding of healthcare communication.

### Abstract

The exponential surge in unstructured healthcare data presents a challenge in extracting actionable insights for healthcare professionals. This study employs Artificial Intelligence (AI), Machine Learning (ML), and Natural Language Processing (NLP) to uncover latent topical features crucial for informing Healthcare Professionals.

Research Questions - 
Part I:

Can Latent Dirichlet Allocation (LDA) unveil latent topical mixtures in medical abstracts?
Can overlaying medical ontologies enrich these latent topics, revealing new relationships and insights?
Part II:

Can enriched medical abstracts support a guided search system for medical professionals, ensuring a common vocabulary?
Background

Healthcare records often lack standardized terminology, leading to potential delays or gaps in patient care. This research aims to harmonize medical terms through AI-ML models trained on medical abstracts. The integration of controlled vocabularies over these models strives to align healthcare professionals' terminologies, enabling semantic search capabilities for better patient outcomes.

Objectives
Train an AI/ML model using LDA to discover latent topics within medical abstracts.
Overlay MeSH & SNOMED medical ontologies to create weighted term-topic and document-topic matrices.
Assess the efficacy of AI/ML-driven approaches in improving healthcare information exploration.
Methods: Data Collection and Sources

Dataset: 14,442 medical abstracts sourced from diverse healthcare repositories.
LDA for Discovering Latent Topics: Tokenization into unigrams/bigrams, TFIDF Count Vectorizer, and hyperparameter-tuned LDA modeling.
Integration of MeSH and SNOMED API: Python program integrating APIs to enrich the term-topic matrix.
Findings
Enhanced Relevance: AI/ML techniques enriched the term-topic matrix with insights from MeSH and SNOMED APIs.
Contextual Importance: Created a medical information matrix enriched with semantic meaning, facilitating a common understanding of medical terminology's contextual relevance.
Implications

This research highlights the potential of advanced AI/ML methodologies in healthcare informatics, especially in:

Information Retrieval: Enhancing retrieval within healthcare by overlaying medical ontologies.
Common Language: Enabling a common language for clinical decision-making, research, and education within healthcare.

