---
layout: otherpage
title: Research
permalink: /research/
---

<!-- ## Current research -->
<p align="center">
    <img style="margin-right: 20px; margin-left: 20px; max-width: 20em;" src="/images/Website fly.svg" alt="drawing of a fly with VNC neurons"/>
</p>
<!-- <img margin-right: 50px; margin-left: 50px; margin-top: 20px; margin-bottom: 20px; src="/images/Website fly.svg" alt="" width="60%" display=block/> -->


I am using computational approaches to study the structure and function of **motor circuits in the fly ventral nerve cord** (VNC, a spinal cord analog). *Drosophila melanogaster* is currently the most complex adult animal to have complete synapse-resolution neural wiring diagrams, called *connectomes*, of its brain and VNC. I use these [connectome](https://www.sciencedirect.com/science/article/pii/S0092867420316834?via%3Dihub) [datasets](https://www.biorxiv.org/content/10.1101/2023.06.05.543757v1) as a basis for modeling neural activity in the VNC. I am especially interested in how descending neurons from the brain converge onto premotor circuits that transform these "walk forward" or "turn left" signals into coordinated muscle movements, and what role proprioceptive reflex circuits within the VNC play in modulating this circuit. I have also started to incorporate a biomechanical model to simulate the fly’s kinematics. I hope that the connectome can provide big-picture insights into the organization of the motor system and generate some predictions I can test in real flies. I am co-advised by [John Tuthill](https://faculty.washington.edu/tuthill/index.html) and [Bing Brunton](https://www.bingbrunton.com/).

<center>
<br><h2>Past projects</h2>
    <h3>Behavioral states and accumulation of sensory evidence in <i>C. elegans</i></h3>
    <img style="margin-right: 20px; margin-left: 20px; max-width: 20em" src="/images/Website worm.svg" alt="drawing of a worm encountering road signs that warn of dangers"/>
</center>
Before graduate school, I worked for 2 years as a research technician in the [Flavell Lab](https://flavell.mit.edu/) at MIT. With postdoctoral researcher Dr. Saba Baskoylu, I studied the way that worms (*C. elegans*) change their behavior when they **accumulate evidence that their environment is undesirable**. The long-term goal of the project was to identify circuit mechanisms by which the nervous system produces an enduring change in mapping from sensory input to behavioral responses. To investigate this, I ran experiments where I optogenetically activated nociceptive sensory neurons and examined the animals’ behavioral responses, as well as companion assays using natural stimuli that the worms find aversive. I also assisted with several other projects in the lab to help quantify neuromodulatory effects on the worms’ locomotion and navigation.


<center>
    <h3>Computational modeling of EEG/MEG currents in human neocortex</h3>
    <img style="margin-right: 20px; margin-left: 20px; max-width: 16em" src="/images/Website EEG.svg" alt="drawing of me with EEG electrodes on, showing neurons in my head and a computer simulation of those neurons"/>
</center>
Electroencephalography (EEG) and magnetoencepholography (MEG) recordings are easy and non-invasive to obtain, and can provide useful biomarkers for clinicians, but it is difficult to understand how the underlying network activity in the brain generates the waveforms you can observe outside of the head. As an undergraduate in the [Jones Lab](https://sites.brown.edu/stephanie-r-jones-lab/) at Brown University, I built upon the computational model the lab had built to relate electrical currents from cortical pyramidal neurons to recorded EEG/MEG signals in order to simulate the **contributions of dendritic calcium spikes to these waveforms**. I updated the model layer 5 pyramidal neurons' calcium channels to better fit electrophysiological recordings of these cells in other mammals, then examine the effects of calcium events on the simulated source-localized EEG signal. The improved model replicated [findings in rats](https://www.nature.com/articles/s41467-017-00282-4) that dendritic calcium spikes have a distinct signature in surface recordings, and found that generally the sustained electrical activity in the distal dendrites during a dendritic calcium spike pushes a significant amount of current down the apical dendrite.