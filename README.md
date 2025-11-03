# rdt_transform_for_tiny_ml_signal_classifiers
## iRDT: 
A transform with **at most 25 code lines**, proved so far a convenient substitute for more sophisticated transforms (e.g. MFCCs) in various signal recognition problems. 
**No multipliers**, **simple algorithm**, one can apply it for various signals by optimzing the delays in the algorithm. 

Particularly **useful for HW-oriented devices** (MCU, FPGAs) in the Tiny-ML context. 
iRDT is implemented here as function nrdt_2025z()

Copyright Radu and Ioana DOGARU radu.dogaru@upb.ro 
Last update: 23 oct. 2025.  

It represents a revised, optimized and simplified code replacement for the older RDT Python code provided in https://github.com/radu-dogaru/NL-CNN-RDT-based-sound-classification-  including JIT and fixed-point (INT32). 

For facile access to datasets in  examples, it is prefferable to run the notebook on Kaggle
<a href="https://colab.research.google.com/github/radu-dogaru/rdt_transform_for_tiny_ml_signal_classifiers/blob/main/nrdt-2025.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Citing This Work
**Relevant papers** 

[0] R. Dogaru and I. Dogaru, "Why RDT ?, "Computational aspects in favor of the RDT transform", oct. 2025 here [https://github.com/radu-dogaru/rdt_transform_for_tiny_ml_signal_classifiers/blob/main/why_RDT.pdf]

[1] R. Dogaru and I. Dogaru, "A low complexity solution for epilepsy detection using an improved version of the reaction-diffusion transform," 2017 5th International Symposium on Electrical and Electronics Engineering (ISEEE), Galati, Romania, 2017, pp. 1-6, doi: 10.1109/ISEEE.2017.8170678.
https://ieeexplore.ieee.org/document/8170678  

[2] R. Dogaru and I. Dogaru, "State of the Art Recognition of Emotions from Speech, Using a Low Complexity Solution Based on Reaction-Diffusion Transform," 2022 International Symposium on Electronics and Telecommunications (ISETC), Timisoara, Romania, 2022, pp. 1-4, doi: 10.1109/ISETC56213.2022.10010234. 
https://ieeexplore.ieee.org/document/10010234

<img width="480" height="360" alt="RDT_explain" src="https://github.com/user-attachments/assets/2a6c6523-7a5d-4153-9dbc-569c8dc30f91" />

## History 
The RDT idea emerged in 2000's inspired from cellular-automata works in the context of finding some conveninet measure to quantify numerically emergent behaviors. See more in:  https://ieeexplore.ieee.org/document/1630267

Later, in 2007 we first expanded it succesfully (introducing the idea of sub-sampling in some m-channels) to sound recognition problems. See more in: https://ieeexplore.ieee.org/document/4410603 

Since then it proved a convenient feature for either audio or bio-medical signals, competing well against traditional spectrogram algorithms. See more here: https://ieeexplore.ieee.org/search/searchresult.jsp?action=search&newsearch=true&matchBoolean=true&queryText=(%22Full%20Text%20Only%22:%22reaction-diffusion%20transform%22)%20AND%20(%22Authors%22:Dogaru)  

