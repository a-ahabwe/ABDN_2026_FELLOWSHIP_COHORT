# ABDN 2026 Cohort Repository

## 🧠 Overview

Welcome to the **ABDN 2026 Participant Repository**.

This repository serves as the central workspace for:

* Lecture materials
* Assignments and exercises
* Participant submissions
* Final research outputs

It is designed to support a **structured, hands-on learning experience** across multiple neuroimaging and neuroscience modalities.

---

## 🔬 Modalities

Participants will engage in one or more of the following tracks:

* **EEG (Electroencephalography)**
* **MRI / fMRI (Magnetic Resonance Imaging / Functional MRI)**
* **Electrophysiology**
* **fNIRS (Functional Near-Infrared Spectroscopy)**

Each modality follows a consistent progression:

> Foundations → Data Acquisition → Data Analysis → Scientific Writing → Final Project

---

## 📁 Repository Structure

```
abdn-2026-cohort/
├── lectures/              # Slides, notes, and resources
│   ├── eeg/
│   ├── mri_fmri/
│   ├── electrophysiology/
│   └── fnirs/
│
├── assignments/           # Tasks and instructions
│   ├── eeg/
│   ├── mri_fmri/
│   ├── electrophysiology/
│   └── fnirs/
│
├── participants/          # Individual participant submissions
│   └── <participant_name>/
│       ├── eeg/
│       ├── mri_fmri/
│       ├── electrophysiology/
│       └── fnirs/
│
├── templates/             # Report + notebook templates
│
├── datasets/              # Links or small datasets (no large files)
│
└── showcase/              # Selected outstanding work
    ├── best_papers/
    └── posters/
```

---

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-ORG/abdn-2026-cohort.git
   cd abdn-2026-cohort
   ```

2. Create your participant folder:

   ```bash
   mkdir -p participants/your_name/{eeg,mri_fmri,electrophysiology,fnirs}
   ```

3. Check your assigned modality and begin with:

   * `lectures/<modality>/`
   * `assignments/<modality>/`

---

## 📥 Submission Guidelines

### 🔹 General Rules

* All work must be submitted via **GitHub (no email submissions)**
* Commit regularly (don’t upload everything at once)
* Use clear commit messages
* Follow the folder structure strictly

---

### 🔹 Folder Naming

Use your **full name in lowercase with underscores**:

```
participants/john_doe/
participants/jane_smith/
```

---

### 🔹 Where to Submit

Submit your work inside your modality folder:

```
participants/<your_name>/<modality>/
```

Example:

```
participants/john_doe/eeg/week_01/
participants/john_doe/mri_fmri/final_project/
```

---

### 🔹 Weekly Submissions

Each week should be organized like this:

```
week_01/
├── README.md          # Summary of what you did
├── analysis.ipynb     # Code / notebook
├── results/           # Figures, outputs
└── data/              # Small processed data only
```

---

### 🔹 Final Project Submission

Your final project must include:

```
final_project/
├── paper.md or paper.pdf
├── code/
├── figures/
└── README.md
```

Your README should include:

* Project title
* Research question
* Dataset used
* Methods
* Key findings

---

## 🔁 Submission Workflow Options

### Option A — Direct Push (Simpler)

1. Clone the repo
2. Add your work
3. Commit and push

```bash
git add .
git commit -m "Week 2 EEG: preprocessing pipeline"
git push
```

---

### Option B — Fork + Pull Request (Recommended for larger cohorts)

1. Fork the repository
2. Clone your fork
3. Create a branch:

```bash
git checkout -b week-02-submission
```

4. Push changes and open a Pull Request

---

## 🧾 File Guidelines

* Use **Jupyter notebooks (.ipynb)** or Python scripts
* Keep files well-documented
* Avoid large datasets (>100MB)
* Use links for external data

---

## 🧠 Expectations

Participants are expected to:

* Engage actively with weekly material
* Complete assignments on time
* Maintain clean, reproducible code
* Document their work clearly
* Collaborate respectfully

---

## 🌟 Showcase

Top submissions will be featured in:

```
showcase/best_papers/
showcase/posters/
```

---

## 🛠 Recommended Tools

* Python (NumPy, SciPy, Matplotlib)
* Jupyter Notebooks
* MNE-Python (EEG)
* EEGLAB
* SPM / FSL (fMRI)

---

## 🤝 Contributing

To improve materials:

1. Create a branch
2. Make changes
3. Submit a pull request

---

## 📬 Contact

For questions, reach out to your TA or program coordinator.

---

## 📄 License

This repository is intended for educational use. Licensing will follow ABDN guidelines.

---

## ✨ Final Note

This repository is not just for submission —
it is your **research workspace, portfolio, and learning journal**.

Take it seriously. Build something meaningful.
# ABDN_2026_FELLOWSHIP_COHORT
