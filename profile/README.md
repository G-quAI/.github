# G-quAI: Predicting Gastrointestinal Cancer Using Quantum AI

G-quAI is a research initiative dedicated to leveraging quantum computing to enhance artificial intelligence (AI) models for the diagnosis and prevention of gastrointestinal (GI) cancers, particularly colorectal cancer (CRC). Our mission is to create more accurate, energy-efficient, and scalable diagnostic tools to improve early cancer detection and patient outcomes worldwide.

---

### The Challenge
Colorectal cancer is a significant global health challenge, with millions of new cases diagnosed annually. While new, non-invasive imaging technologies like capsule endoscopy can generate comprehensive views of the GI tract, they produce an unprecedented volume of image data. Analyzing this data is a massive challenge for medical teams and classical high-performance computing, which is often costly, energy-intensive, and faces limitations in scalability and diagnostic accuracy.

---

### Our Solution
We are developing hybrid quantum-classical pipelines to address the bottlenecks of classical AI. By mapping complex image data into the exponentially large computational space of quantum systems, our models aim to uncover subtle patterns that classical methods might miss, leading to more robust and accurate diagnoses.

Our work is currently focused on two distinct quantum approaches:
1. Analog Quantum Reservoir Computing (QRC) with Neutral Atoms.
2. Digital Quantum Neural Networks (QNNs) with Superconducting Qubits.

---
### Repositories
Our main repository, G-quAI-Pipelines, serves as a central hub that documents and links to the specific implementations of our two primary research tracks.

- [**G-quAI-Pipelines**](https://github.com/G-quAI/G-quAI-Pipelines) (Hub)  
From there, you can explore our two specialized repositories:

  1. [**Neutral-Atom-QGARS**](https://github.com/NunoMBatista/Neutral-Atom-QGARS/tree/main)  
     This repository contains our implementation of a **Quantum-Guided Autoencoder with a Reservoir Surrogate (QGARS)**. This pipeline uses a classical autoencoder to learn compact image representations, which are then encoded into the parameters of a **Rydberg Hamiltonian** in a neutral-atom quantum reservoir. The reservoir's dynamics generate high-dimensional quantum embeddings that are used by a classical linear classifier for polyp detection.




  3. [**Superconducting-Neural-Network**](https://github.com/NunoMBatista/Superconducting-Neural-Network/tree/main)  
     This repository contains our implementation of a **Quantum Neural Network (QNN)** designed for gate-based superconducting quantum computers. This approach uses a classical autoencoder for dimensionality reduction, followed by the **Flexible Representation of Quantum Images (FRQI)** to encode image features into a quantum state. **A variational quantum circuit** then processes the state to classify the image as containing a polyp or not.
     
---

### Members:  
- [Ana Beatriz Morgado](https://www.linkedin.com/in/ana-beatriz-morgado-6b20362b1)  
- [Gabriel Falcão](https://pt.linkedin.com/in/gfalcao)  
- [Jorge Lobo](https://pt.linkedin.com/in/jorge-lobo-8056a948)  
- [Sagar Pratapsi](https://www.linkedin.com/in/spratapsi/)  
- [Oscar Ferraz](https://www.linkedin.com/in/oscarferraz/)  
- [Nuno Batista](https://www.linkedin.com/in/nuno-batista-785440257/)  
