# BCI-Development-Playground

## Foundational Knowledge / Neuroscience and computational fundamentals.

### 1. Core Neuroscience & BCI Theory
- **[Medical Neuroscience (Duke University)](https://www.coursera.org/learn/medical-neuroscience):** A comprehensive course on the functional organization and neurophysiology of the human central nervous system and the biological basis of BCI.
- **[Computational Neuroscience (University of Washington)](https://www.coursera.org/specializations/computational-neuroscience):** Bridges biology and computation by teaching how to model neurons and networks. The "how" we can mathematically describe neural activity.
- **[The Mind and the Machine (University of Colorado)](https://www.coursera.org/specializations/mind-machine):** Directly addresses BCI applications, signal processing for neural data (like EEG), and the practical aspects of creating a BCI. The "what" we build with this knowledge.

### 2. Core Technical Skills
- **Linear Algebra:** [3Blue1Brown's Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDMSUeMus_o2aD_L-BOI6x-h) - A guide to linear algebra, which is the bedrock of machine learning and signal processing.
- **Digital Signal Processing (DSP):** [Resource Link] - Critical for cleaning, filtering, and interpreting noisy neural data. *(Suggestion: Find a good DSP tutorial or course to link here)*.
- **Python for Data Science:** [Resource Link] - Essential for implementing BCI algorithms. *(Suggestion: Link a relevant course from Coursera, Udemy, or freeCodeCamp)*.

## 💻 Development Playground

This section contains the tools and data you need to start building.

### 1. Software & Libraries
- **[MNE-Python](https://mne.tools/stable/index.html):** The essential open-source Python package for offline analysis and visualization of neurophysiological data (EEG, MEG, ECoG).
- **[BrainFlow](https://brainflow.org/):** A fantastic, user-friendly library for acquiring data from a wide variety of EEG headsets in real-time.
- **[PyBCI](https://pybci.com/):** A high-level Python library designed for rapid prototyping of BCIs with real-time data streams.
- **[OpenViBE](http://openvibe.inria.fr/):** A popular open-source software platform for designing and testing BCIs with a graphical, no-code-required interface.

### 2. Public Datasets
- **[MOABB (Mother of all BCI Benchmarks)](https://neurotechx.github.io/moabb/):** A Python framework that provides easy access to dozens of BCI datasets (Motor Imagery, SSVEP, P300) and tools for benchmarking algorithms.
- **[PhysioNet](https://physionet.org/):** A massive repository of medical data, including many EEG datasets for BCI experiments.
- **[BCI Competition Datasets](http://www.bbci.de/competition/):** Classic datasets from past BCI competitions, often used as benchmarks in academic papers.

### 3. Beginner Project Ideas
- **Motor Imagery BCI:** The "Hello, World!" of BCI. A project to classify whether a user is imagining left or right-hand movement from EEG data.
- **P300 Speller:** A tutorial on building a simple speller based on the P300 event-related potential, where the brain emits a unique signal when seeing a rare or desired item.
- **SSVEP Controller:** A project where looking at flickering lights at different frequencies can be used to issue commands or control a cursor.

## 🚀 The BCI Ecosystem

An overview of the hardware, companies, and communities driving the field forward.

### 1. BCI Hardware
- **[OpenBCI](https://openbci.com/):** The leading open-source hardware and software platform for building your own research-grade BCI.
- **Consumer/Prosumer Headsets:** TODO list devices like the Unicorn Brain Interface, Muse, or Emotiv for context on accessible hardware.

### 2. Companies & Startups

#### Europe
*   **[MindMaze (Switzerland)](https://www.mindmaze.com/):** Pioneer in digital neurotherapeutics using VR and AI to help patients recover from neurological injuries.
*   **[CereGate (Germany)](https://ceregate.com/):** Develops a software platform to use existing neurostimulators as a BCI for providing new sensory information to patients.
*   **[BIOS Health (United Kingdom)](https://www.bios.health/):** Creates a full-stack neural interface platform using AI to decode and modulate signals on the nervous system to treat chronic disease.
*   **[Wise (Italy)](https://www.wiseneuro.com/):** Specializes in novel, stretchable electrodes for less invasive and more effective neuromodulation.
*   **[Salvia Bioelectronics (Netherlands)](https://www.salvianeuro.com/):** Develops minimally invasive bioelectronic foils for treating chronic migraines through neurostimulation.
*   **[Inbrain Neuroelectronics (Spain)](https://www.inbrain-neuroelectronics.com/):** Uses high-resolution graphene implants for ultra-precise mapping and therapy of brain conditions like epilepsy.

#### North America (Examples for Expansion)
*   **[Neuralink (USA)](https://neuralink.com/):** Developing high-bandwidth, implantable BCIs for direct neural control.
*   **[Synchron (USA)](https://synchron.com/):** Creating an endovascular, stent-based neural interface that avoids open brain surgery.
*   **[Kernel (USA)](https://www.kernel.com/):** Building non-invasive helmets for recording brain activity with high fidelity.
*   **[Paradromics (USA)](https://paradromics.com/):** Focused on high-data-rate interfaces to address data bottlenecks between the brain and computers.

```
