# BCI-Development-Playground

List of resources for learning, developing, and exploring the field of Brain-Computer Interfaces.

##  Foundational Knowledge
### 1. Core Neuroscience & BCI Theory
- **[Medical Neuroscience (Duke University)](https://www.coursera.org/learn/medical-neuroscience):** A comprehensive course on the functional organization and neurophysiology of the human central nervous system and the biological basis of BCI.
- **[Computational Neuroscience (University of Pennsylvania)](https://www.coursera.org/learn/computational-neuroscience):** Bridges biology and computation by teaching how to model neurons and networks. The "how" we can mathematically describe neural activity.
- **[The Mind and the Machine (University of Colorado)](https://www.coursera.org/specializations/mind-machine):** Directly addresses BCI applications, signal processing for neural data (like EEG), and the practical aspects of creating a BCI. The "what" we build with this knowledge.

### 2. Core Technical Skills
- **Linear Algebra:** **[3Blue1Brown's Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDMSUeMus_o2aD_L-BOI6x-h)** - A visual, intuitive guide to linear algebra, which is the bedrock of machine learning and signal processing.
- **Digital Signal Processing (DSP):** **[DSP Illustrated (Online Book)](https://dspillustrations.com/)** or **[Coursera's Digital Signal Processing (EPFL)](https://www.coursera.org/specializations/digital-signal-processing)** - Critical for cleaning, filtering, and interpreting noisy neural data. These resources include Python examples for practical application.
- **Python for Data Science:** **[Data Analysis with Python (freeCodeCamp Course)](https://www.youtube.com/watch?v=r-uOLxNrNk8)** or **[Coursera's Python for Everybody (University of Michigan)](https://www.coursera.org/specializations/python-for-everybody)** - Essential for implementing BCI algorithms, with focus on libraries like NumPy, Pandas, and SciPy.

## Key BCI Paradigms

Understanding these core concepts is key to working with the projects and datasets below.

- **Motor Imagery (MI):** The act of imagining a motor movement without any actual muscle activation. The brain patterns for imagined and real movements are similar, allowing a BCI to detect a user's intent (e.g., imagining left vs. right-hand movement).
- **P300 Event-Related Potential (ERP):** A specific brain signal that appears as a positive voltage spike roughly 300ms after a person sees a rare or significant "target" stimulus. This is often used for BCI spellers, where target letters flash in a grid.
- **Steady-State Visually Evoked Potential (SSVEP):** A natural brain response to looking at a light flickering at a specific frequency. By having multiple lights flickering at different frequencies, a BCI can determine which light the user is looking at, allowing them to issue commands.

## Development Playground

This section contains the tools and data you need to start building.

> **Pro Tip:** Start with offline datasets before moving to real-time hardware. This will help you learn the fundamentals of signal processing and machine learning without the added frustration of dealing with noisy live signals and hardware issues.

### 1. Software & Libraries
- **[MNE-Python](https://mne.tools/stable/index.html):** The essential open-source Python package for offline analysis and visualization of neurophysiological data (EEG, MEG, ECoG).
- **[BrainFlow](https://brainflow.org/):** User-friendly library for acquiring data from a wide variety of EEG headsets in real-time.
- **[PyBCI](https://github.com/LMBooth/pybci):** A high-level Python library designed for rapid prototyping of BCIs with real-time data streams.
- **[OpenViBE](http://openvibe.inria.fr/):** A popular open-source software platform for designing and testing BCIs with a graphical, no-code-required interface.

### 2. Public Datasets
- **[MOABB (Mother of all BCI Benchmarks)](https://moabb.neurotechx.com/docs/index.html):** A Python framework that provides easy access to dozens of BCI datasets (Motor Imagery, SSVEP, P300) and tools for benchmarking algorithms.
- **[PhysioNet](https://physionet.org/):** A massive repository of physiological signals and medical data, including many EEG datasets for BCI experiments.
- **[BCI Competition Datasets](http://www.bbci.de/competition/):** Old classic datasets from past BCI competitions, often used as benchmarks in academic papers.

### 3. Beginner Project Ideas
- **Motor Imagery BCI:** The "Hello, World!" of BCI. A project to classify whether a user is imagining left or right-hand movement from EEG data.
  - ***Tutorial tip:*** *Use MOABB to easily download datasets and MNE-Python to build the classification pipeline.*
- **P300 Speller:** Build a simple speller based on the P300 event-related potential.
  - ***Tutorial tip:*** *This is a paradigm for a real-time app using a headset compatible with BrainFlow.*
- **SSVEP Controller:** A project where looking at flickering lights at different frequencies can be used to issue commands or control a cursor.
  - ***Tutorial tip:*** *Try prototyping this quickly with OpenViBE's graphical designer before writing any code.*

## The BCI Ecosystem

An overview of the hardware, companies, and communities driving the field forward. Join communities like **[NeuroTechX](https://neurotechx.com/)** or Reddit's **[r/BCI](https://www.reddit.com/r/BCI/)** for discussions.

### 1. BCI Hardware
- **[OpenBCI](https://openbci.com/):** The leading open-source hardware and software platform for building your own research-grade BCI.
- **Consumer/Prosumer Headsets:** Affordable options for entry-level experimentation:
    - **[Unicorn Brain Interface](https://www.unicorn-bi.com/):** A low-cost, 8-channel EEG headset ideal for beginners, with easy integration via BrainFlow.
    - **[Muse (InteraXon)](https://choosemuse.com/):** A consumer-grade EEG headband focused on meditation, with an SDK for custom BCI apps.
    - **[Emotiv](https://www.emotiv.com/):** Sells wireless headsets like the EPOC+ (14 channels), popular for research and emotion detection features.
    - **NextMind (acquired by Snap):** A non-invasive, SSVEP-based visual BCI sensor. While the product is no longer sold publicly, its technology represents a key area of consumer BCI development.

### 2. Companies & Startups

#### Europe
- **[MindMaze (Switzerland)](https://www.mindmaze.com/):** Pioneer in digital neurotherapeutics using VR and AI to help patients recover from neurological injuries.
- **[CereGate (Germany)](https://ceregate.com/):** Develops a software platform to use existing neurostimulators as a BCI for providing new sensory information to patients.
- **[BIOS Health (United Kingdom)](https://www.bios.health/):** Creates a full-stack neural interface platform using AI to decode and modulate signals on the nervous system to treat chronic disease.
- **[Wise (Italy)](https://www.wiseneuro.com/):** Specializes in novel, stretchable electrodes for less invasive and more effective neuromodulation.
- **[Salvia Bioelectronics (Netherlands)](https://www.salvianeuro.com/):** Develops minimally invasive bioelectronic foils for treating chronic migraines through neurostimulation.
- **[Inbrain Neuroelectronics (Spain)](https://www.inbrain-neuroelectronics.com/):** Uses high-resolution graphene implants for ultra-precise mapping and therapy of brain conditions like epilepsy.

#### North America
- **[Neuralink (USA)](https://neuralink.com/):** Developing high-bandwidth, implantable BCIs for direct neural control.
- **[Synchron (USA)](https://synchron.com/):** Creating an endovascular, stent-based neural interface that avoids open brain surgery.
- **[Kernel (USA)](https://www.kernel.com/):** Building non-invasive helmets for recording brain activity with high fidelity.
- **[Paradromics (USA)](https://paradromics.com/):** Focused on high-data-rate interfaces to address data bottlenecks between the brain and computers.
- **[Blackrock Neurotech (USA)](https://blackrockneurotech.com/):** A foundational company providing the "Utah Array" for high-resolution neural recording, used in countless research and clinical trials.
- **[CTRL-labs (acquired by Meta, USA)](https://tech.fb.com/ar-vr/portal-rebrand-meta-quest-2-active-pack/):** Develops wristband-based neural interfaces (EMG) for detecting motor signals as a form of BCI input.

## 📚 Further Reading & Watching

### Seminal Papers
- **[Vidal, 1973 - "Toward direct brain-computer communication"](https://ieeexplore.ieee.org/document/1705768):** The paper widely credited with coining the term "Brain-Computer Interface" and laying out the initial vision.
- **[Farwell & Donchin, 1988 - "Talking off the top of your head"](https://www.sciencedirect.com/science/article/abs/pii/0013469488901496):** The groundbreaking paper that introduced the P300 speller.

### Talks
- **[Mary Lou Jepsen: How we can use light to see deep inside our bodies and brains](https://www.youtube.com/watch?v=2w2_n_6aO6Q):** A TED talk on the future of non-invasive, high-resolution optical imaging for brain activity.
