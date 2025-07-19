# BrainForm 🎮🧠

**BrainForm** is a serious game developed using **Unity 2022.3** that integrates the native package for the **Unicorn EEG** device to create a gamified **Brain-Computer Interface (BCI)** training system. It is designed for scalable data collection using a minimal, wearable hardware setup.

---

## 🧩 About the Project

BrainForm is structured as a **2D platformer** featuring:

- A **tutorial level** introducing players to a simplified version of the experimental BCI tasks.
- A **main level** that contains the complete task sequence for gameplay-based EEG training and evaluation.

The game uses **free visual assets** from the Unity Asset Store and supports real-time EEG signal processing, quality estimation, and classification through the Unicorn package's native features.

---

## 🧠 Core BCI Features

- Integration with **Unicorn EEG device** via native Unity package.
- Signal quality estimation and configurable BCI processing pipeline.
- Proprietary **LDA classifier** for online EEG-based control.
- Real-time feedback loop and logging for research-grade data collection.

---

## 🧪 Research Context

BrainForm was designed to explore two main questions:

1. **How do users develop BCI control skills** over repeated gameplay sessions?
2. **What are the perceptual and performance-related impacts** of two different visual stimulation textures (with a focus on visual fatigue)?

### Key Findings

- **No significant performance differences** between stimulation textures.
- **Visual fatigue increased** with session count, notably in ocular irritation.
- **Positive user experience** indicated by the Game Experience Questionnaire (GEQ), especially in:
  - Flow
  - Positive Affect
  - Challenge
- **Online performance metrics confirmed learning effects** across sessions:
  - Improved **Task Accuracy**
  - Reduced **Task Time**
  - Increased **Information Transfer Rate (ITR)**

---

## 📊 Experimental Setup

- Within-subject design
- Multiple gameplay runs
- Two BCI tasks of varying complexity
- Post-session self-report questionnaires

---

## 🚀 Getting Started

### Prerequisites for Building

- **Unity 2022.3**
- A compatible **Unicorn EEG device**
- Unicorn Unity package installed and activated

### Run Instructions

1. Clone this repository.
2. Open the project in Unity 2022.3.
3. Make sure the Unicorn EEG drivers and SDK are installed.
4. Attach your EEG device and start the game from the Unity Editor or build.
5. Follow the in-game instructions to begin training.

---

## 🙌 Acknowledgements

- **Unity Asset Store** for free 2D visual assets.
- All participants who contributed to the evaluation study.

---

## 📫 Contact

For questions, collaborations, or access to experimental data, please reach out via the Issues page or contact the project maintainers directly.

---

> *BrainForm shows great potential for robust, user-friendly BCI data collection and long-term user engagement in neurotechnology research.*

