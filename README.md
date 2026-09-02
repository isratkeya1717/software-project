### Task: Add Card Feature

**Description:**
Implement the card feature for the Air Ticket Management System.

**Tasks:**

* Create the card UI.
* Add required card information.
* Implement responsive design.
* Connect the card with the required functionality.
* Test the card feature.
* Commit the changes to the `feature-card` branch.
* Merge the completed feature into the `main` branch.

**Git Branch:**
`feature-card`

**Expected Result:**
The card feature should be successfully implemented, tested, committed, pushed to GitHub, and merged into the `main` branch.
# PIGMA Module

## Overview

This module implements the **PIGMA (Personalized Intelligent Graph Machine Architecture)** component of the Software Project.

The purpose of this module is to develop and integrate the PIGMA-based approach into the overall system while keeping the implementation modular, maintainable, and easy to integrate with other project components.

## Objectives

* Implement the PIGMA architecture.
* Develop the required data preprocessing pipeline.
* Construct and process graph-based representations.
* Implement the core PIGMA model/components.
* Evaluate the model performance.
* Integrate the PIGMA module with the main project.

## Project Structure

```text
pigma/
├── data/
├── preprocessing/
├── graph/
├── model/
├── evaluation/
├── utils/
└── README.md
```

## Main Components

### 1. Data Preprocessing

Handles data cleaning, transformation, normalization, and preparation for the PIGMA model.

### 2. Graph Construction

Converts the processed data into an appropriate graph representation for graph-based learning.

### 3. PIGMA Model

Contains the core implementation of the PIGMA architecture and its required components.

### 4. Evaluation

Evaluates the model using appropriate performance metrics and experimental results.

## Workflow

```text
Raw Data
   ↓
Data Preprocessing
   ↓
Graph Construction
   ↓
PIGMA Model
   ↓
Prediction / Output
   ↓
Performance Evaluation
```

## Development

The PIGMA module is developed separately using a dedicated Git branch:

```text
pigma
```

Changes are committed to the feature branch and then merged into the main branch through a Pull Request after review.

## Git Workflow

```bash
git switch main
git pull origin main

git switch -c pigma

# Add and modify PIGMA files

git add .
git commit -m "Implement PIGMA module"
git push -u origin pigma
```

After pushing the branch, create a Pull Request:

```text
pigma → main
```

After review and approval, the changes can be merged into the `main` branch.

## Status

* [ ] Data preprocessing
* [ ] Graph construction
* [ ] PIGMA architecture
* [ ] Model training
* [ ] Model evaluation
* [ ] Integration with main project
* [ ] Documentation

## Contributors

**Shorna**

PIGMA Module Developer
