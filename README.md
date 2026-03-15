SDR Knowledge Graph and NER Extraction Experiments

This repository contains the datasets, scripts, and outputs used for the study:

“LLM-Driven Information Extraction from the UK SDR Framework: A Case Study of Sustainability Regulation.”

The project evaluates multiple pipelines for extracting entities and relationships from the UK Sustainability Disclosure Requirements (SDR) policy document.

Project Structure
Source Document

SDR_Implementation_Update_2024.pdf

Primary corpus used in the study.
This document contains the regulatory text from which entities and relationships are extracted.

Extraction Pipelines

The study evaluates three extraction approaches:

Prompt-based extraction (P1)

Prompt-based extraction (P2)

Neo4j LLM Graph Builder extraction

Each pipeline produces entity and relationship outputs that are evaluated using semantic validation and LLM-based judging.

Files Description
Neo4j Schema

NEO4J_LABELS.xlsx

Summary Dashboard: https://lookerstudio.google.com/s/kcWnM9LnUzo
