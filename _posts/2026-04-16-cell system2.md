---
title: Cell Systems: The Minority in Command: Pancreatic Islet δ and α Cells Dictate β Cell Rhythmicity
image: images/sss.png
author: renhuixia
tags: publication
---

Blood glucose homeostasis is the core foundation for maintaining normal metabolism in the body. As the central functional unit regulating blood glucose, the physiological function of pancreatic islets highly depends on the communication among various types of cells within them. Islets are mainly composed of 80% insulin-secreting β cells, 15% glucagon-secreting α cells, and 5% somatostatin-secreting δ cells, closely arranged to form a complex paracrine regulatory network. Under glucose stimulation, islets generate rhythmic calcium oscillation activation signals. Different islets exhibit three oscillation modes: fast (20 seconds), slow (200 seconds), and mixed (20/200 seconds). However, the mechanisms underlying the formation of these different oscillation modes have long remained unclear.

On April 16, 2026, Chao Tang’s team from the Center for Quantitative Biology at Peking University and Huixia Ren’s team from the Chinese Institute for Medical Research (CIMR, Beijing) published a research article titled Pancreatic islet oscillation rhythmicity arises from δ and α cell interactions in the journal Cell Systems. This study discovered that the minority δ cells and α cells within the islet constitute the core network regulating β cell rhythmicity. By combining microfluidic technology, mathematical modeling, and in vivo imaging, the team systematically elucidated the core mechanism by which the paracrine interactions between δ and α cells regulate β cells to form three calcium oscillation modes, revealing a novel mechanism by which islets encode blood glucose concentrations through oscillation patterns.

**1. Technological Innovation: Building a High-Throughput Islet Function-Structure Correlated Imaging System**
Islet diameters range from 50 to 200 μm. To achieve stable high-throughput perfusion and synchronized imaging of islets of different sizes, the research team independently developed a microfluidic chip (Patent No. ZL 2024 1 0739918.1), capable of simultaneously imaging the functional activity of 8 islets. Meanwhile, they constructed a transgenic mouse model with red fluorescent labeling for α cells and green fluorescent labeling for whole-islet calcium signals. Combined with two-photon microscopy, this enabled precise correlative analysis of islet functional activity and three-dimensional structure. Based on this technical system, the team found that under repeated high-glucose stimulation, the calcium oscillation mode of the same islet was highly stable and reproducible. This confirmed that the islet oscillation mode is an inherent physiological property, laying the foundation for subsequent mechanistic studies.
{% include figure.html image="images/Cellsystem2026b-1.png" %}

Figure 1: To explore the relationship between glucose-stimulated islet calcium activity and structure, the team designed an integrated microfluidic chip for synchronized activity imaging of 8 islets, followed by two-photon microscopy imaging of the islet structure.

**2. Islet Oscillation Mode Heterogeneity is Determined by the Number of α Cells**
High-glucose stimulation experiments showed that the islet calcium oscillation mode has a quantitative dependence on the number of α cells (Figure 2). When the number of α cells in an islet is greater than 40, it exhibits fast oscillations; when the number is less than 40, it exhibits slow oscillations. Exogenous intervention experiments further verified this regulation: supplementing glucagon converted all islets to fast oscillations, independent of α cell number; supplementing somatostatin induced a shift to slow oscillations, but the oscillations still depended on the α cell number (1 μM somatostatin raised the α cell number threshold for fast oscillations from 40 to 100). These results clarify that the islet oscillation mode is synergistically regulated by paracrine signals from δ cells (secreting somatostatin) and α cells (secreting glucagon).
{% include figure.html image="images/Cellsystem2026b-2.png" %}

Figure 2: Islet oscillation modes depend on the number of α cells and can be modulated by exogenous glucagon and somatostatin.

**3. Pharmacological and Optogenetic Inhibition of δ Cells Reversibly Switches Islet Oscillation Modes**
Since δ cells account for only 5% of total islet cells, the team conducted pharmacological and optogenetic perturbation experiments to verify the regulatory role of endogenous hormones from this small cell population (Figure 3). By using the Sstr2 receptor antagonist CYN to relieve the inhibition of α cells by δ cells, the release of endogenous glucagon reversibly converted slow oscillations into fast oscillations. The oscillation mode recovered after drug washout. Optogenetic inhibition of δ cells achieved the same mode switch, and this process could occur repeatedly within a single islet. These results indicate that endogenous hormone secretion by the minority δ and α cells plays a crucial role in islet rhythm regulation: **α cell activation drives fast oscillations, δ cell activation drives slow oscillations**, and the endogenous hormone interaction between the minority δ and α cells is the core driving force of islet rhythm regulation.
{% include figure.html image="images/Cellsystem2026b-3.png" %}

Figure 3: Pharmacological and optogenetic perturbation of δ cells reversibly switches islet oscillation modes.

**4. Fast-Mixed-Slow Oscillation Modes are Three Continuous Physiological States Regulated by δ-α Cells**
To quantitatively study how islet δ and α cells control the three calcium oscillation modes, the research team continuously increased the somatostatin concentration (secreted by δ cells) in islets with different α cell numbers. They found that as the somatostatin concentration increased, the islet transitioned sequentially from fast oscillation → mixed oscillation → slow oscillation (Figure 4). Interestingly, arranging islets continuously by their α cell numbers revealed the same pattern: islets with the most α cells showed fast oscillations, those with the fewest showed slow oscillations, and those in the middle showed mixed oscillations. These results indicate that fast, mixed, and slow oscillations are **three continuous physiological states** of the islet, with mixed oscillations being a transitional state between fast and slow. The strength of the paracrine interaction between δ and α cells is the core parameter determining the oscillation mode.

{% include figure.html image="images/Cellsystem2026b-4.png" %}
Figure 4: Fast-mixed-slow oscillation modes are three continuous states mediated by δ and α cells, with the mixed mode acting as a transitional state.

**5. Mathematical Modeling Reveals the Transition Between Three Oscillation Modes is a Hopf Bifurcation**
To quantitatively elucidate the regulatory rules of δ-α cells, the team simplified the islet into a coupled oscillator system of α, β, and δ cells. They built a mathematical model using **α→β cell stimulation** and **δ→α cell inhibition** as core parameters (Figure 5). This model accurately reproduced the three calcium oscillation modes and revealed the core logic of mode transitions: slow oscillation corresponds to weak α→β stimulation, fast oscillation corresponds to strong stimulation, and mixed oscillation represents a limit cycle state of alternating strong and weak stimulation. Bifurcation phase diagram analysis further confirmed that the transition between the three islet oscillation modes is a **Hopf bifurcation**, providing quantitative biological theoretical support for islet rhythm regulation.

{% include figure.html image="images/Cellsystem2026b-5.png" %}

Figure 5: The mathematical model replicates that the three continuous fast-mixed-slow oscillation modes mediated by δ and α cells represent a Hopf bifurcation.

**6. *In Vivo* Islets Precisely Encode Blood Glucose Concentration Through Oscillation Modes**

Based on the *in vivo* cellular activation characteristics (α cells respond to basal glucose, δ cells respond to high glucose), the team investigated whether islet oscillation modes serve as an *in vivo* blood glucose encoding mechanism. The results showed that at fasting blood glucose levels of 5-7 mM, islets exhibit fast oscillations (Figure 6); when blood glucose rises to 7-20 mM, they switch to slow oscillations; once blood glucose returns to basal levels, the oscillation mode synchronizes back. This demonstrates that islets achieve precise encoding of blood glucose concentrations through the δ-α cell-regulated calcium oscillation mode, proposing a novel mechanism for the body's perception and encoding of blood glucose.

{% include figure.html image="images/Cellsystem2026b-6.png" %}
Figure 6: In vivo islets sense and encode blood glucose concentration through oscillation modes.

**Summary**
This study supplements the traditional β-cell-centric view of islet function, establishing that δ and α cells form the core network for islet rhythm regulation: glucagon secreted by α cells drives fast calcium oscillations, somatostatin secreted by δ cells maintains slow calcium oscillations, and their interaction determines the islet oscillation mode. The research established a mathematical model for quantitative islet function studies and revealed a novel mechanism of blood glucose encoding by islet rhythm at the *in vivo* level, providing a new perspective for understanding blood glucose homeostasis.

Watch the video introduction at https://www.youtube.com/watch?v=KraBOIOCIM4&t=3s


