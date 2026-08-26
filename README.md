# A World Away: Hunting for Exoplanets with AI

**Machine learning for automated exoplanet classification using NASA mission data**

This project was created as a practical demonstration for members of **Durham University's Computing Society**, delivered on 24 November 2025. It explores how machine learning can be applied to one of astronomy's most interesting data problems: identifying exoplanets from observations collected by space missions.

The project was inspired by NASA's **A World Away: Hunting for Exoplanets with AI** challenge and uses publicly available exoplanet data to demonstrate the difference between **supervised and unsupervised machine learning**, from data preparation through to model interpretation.

The repository contains the analysis notebook and an exoplanet dataset used throughout the demonstration.

---

## Why this project matters

Finding exoplanets involves working with large datasets containing measurements such as orbital period, transit duration, planetary radius and other characteristics of observed systems. Missions including **Kepler, K2 and TESS** have produced enormous quantities of publicly available data, creating an ideal environment for applying machine learning techniques.

This project turns that scientific problem into an accessible, hands-on machine learning workflow.

The interesting part is the combination of skills involved:

* **Real-world data science:** working with scientific data rather than a deliberately clean teaching dataset.
* **Machine learning:** understanding and applying both supervised and unsupervised approaches.
* **Data preprocessing:** preparing variables for meaningful analysis and modelling.
* **Feature reasoning:** considering how astronomical measurements influence classification.
* **Python development:** using a notebook-based workflow for exploration, experimentation and communication.
* **Scientific problem solving:** translating a research problem into a computational classification task.
* **Technical communication:** designing the project specifically to teach other computing students how the techniques work.
* **Applied AI:** connecting machine learning methodology to a genuine research problem with practical relevance.

The project demonstrates an ability to move from **problem definition → data → preprocessing → modelling → interpretation**, which is the core workflow behind many applied machine learning projects.

---

## What the project demonstrates

### 1. Supervised machine learning

The project investigates supervised learning using labelled exoplanet observations.

The underlying problem is a classification task where observations can contain information associated with:

* Confirmed exoplanets
* Planetary candidates
* False positives

This provides a useful setting for demonstrating how labelled data can be used to train a model to recognise patterns in previously observed examples.

### 2. Unsupervised machine learning

The project also demonstrates unsupervised learning, providing a contrast with classification.

Without relying on known labels, unsupervised techniques can be used to investigate the underlying structure of the dataset and identify groups or patterns within the observations.

Putting the two approaches side by side provides a practical demonstration of an important machine learning distinction:

| Approach                  | Input                   | Goal                             |
| ------------------------- | ----------------------- | -------------------------------- |
| **Supervised learning**   | Features + known labels | Learn to predict classifications |
| **Unsupervised learning** | Features without labels | Discover structure and patterns  |

This comparison is particularly valuable because it focuses on **why** a technique is appropriate for a problem, rather than treating machine learning as a collection of algorithms to run.

---

## Data science skills

Working with the exoplanet dataset requires decisions about how raw scientific data should be represented before it can be passed to a machine learning model.

The project demonstrates experience with:

* Dataset inspection
* Data cleaning
* Feature selection
* Handling relevant variables
* Preparing data for machine learning
* Exploring relationships between variables
* Comparing modelling approaches
* Interpreting model outputs

These steps are essential in practical machine learning. Model selection alone does not determine the quality of a result. The way data is understood and prepared can have a substantial impact on performance.

---

## Scientific and domain knowledge

The project is grounded in the **transit method** of exoplanet detection.

When a planet passes between its host star and an observing spacecraft, the measured brightness of the star decreases. Repeated observations of these changes can provide evidence of an orbiting planet.

This gives the machine learning problem a meaningful physical basis. Variables in the dataset correspond to measurable properties of astronomical observations rather than arbitrary numerical features.

That makes the project an example of **domain-informed machine learning**, where understanding the underlying problem helps guide the computational approach.

---

## Engineering and development skills

Beyond the machine learning concepts, the project demonstrates several practical software development skills:

* **Python**
* **Jupyter Notebook**
* **Data analysis**
* **Machine learning workflows**
* **Working with CSV datasets**
* **Exploratory analysis**
* **Reproducible experimentation**
* **Communicating technical results through executable documentation**

The repository is intentionally compact, making the relationship between the dataset and the analysis straightforward to follow.

---

## Teaching and communication

A major part of the project's purpose was educational.

The project was developed to be delivered to members of **Durham University's Computing Society**, meaning the technical work had to be understandable to an audience with varying levels of experience.

That required more than implementing a model. The project had to communicate:

1. What the problem is.
2. Where the data comes from.
3. What the features represent.
4. Why preprocessing matters.
5. How supervised learning works.
6. How unsupervised learning differs.
7. What the resulting models tell us.
8. How machine learning can contribute to scientific research.

This makes the repository both a technical project and an example of **technical communication and knowledge sharing**.

---

## Project structure

```text
AWorldAway-HuntingForExoplanetsWithAI/
│
├── dataex.ipynb       # Data exploration and machine learning analysis
├── exoplanets.csv     # Exoplanet dataset
└── README.md          # Project documentation
```

The repository currently contains the analysis notebook and the associated exoplanet dataset.

---

## The challenge

The project was based on NASA's **A World Away: Hunting for Exoplanets with AI** challenge.

The original challenge asks participants to build an AI or machine learning system using NASA's open-source exoplanet datasets, with the aim of identifying exoplanets and providing a way for users to interact with the resulting system. It specifically highlights datasets from missions including Kepler, K2 and TESS, as well as the importance of preprocessing and model selection.

This project focuses on the machine learning side of that challenge and uses it as a practical vehicle for demonstrating core ML concepts.

---

## Skills demonstrated

### Machine Learning

* Supervised learning
* Unsupervised learning
* Classification
* Clustering and pattern discovery
* Model comparison
* Feature analysis

### Data Science

* Exploratory data analysis
* Data preprocessing
* Feature selection
* Working with scientific datasets
* Interpreting relationships between variables

### Programming

* Python
* Jupyter
* CSV data handling
* Data analysis workflows
* Reproducible experimentation

### Scientific Computing

* Translating an astronomy problem into a computational problem
* Understanding transit-based exoplanet detection
* Working with NASA-derived scientific datasets
* Applying machine learning to astronomical observations

---

## Getting started

Clone the repository:

```bash
git clone https://github.com/TwelveSilverCrows/AWorldAway-HuntingForExoplanetsWithAI.git
cd AWorldAway-HuntingForExoplanetsWithAI
```

Open `dataex.ipynb` in Jupyter Notebook, JupyterLab or another compatible notebook environment and run the analysis.

---

## Background

The project was created in response to the NASA Space Apps Challenge prompt:

**A World Away: Hunting for Exoplanets with AI**

The challenge highlights the growing volume of exoplanetary data produced by missions such as Kepler, K2 and TESS, and the opportunity for machine learning to assist with the identification of exoplanets within those datasets.

---

## Author

**TwelveSilverCrows**

Built as an educational machine learning project for **Durham University's Computing Society**.
