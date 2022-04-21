## Subsampling on large datasets

This project is a set of scripts for creating validation and training sets for the CBDA machine learning project.

The detailed ideas and running instructions are in the file **instruction.md**.

The idea is to use machine learning to examine patient data, including patient outcomes, using machine learning algorithms, to determine those patient attributes that best determine patient outcomes, and how those attributes map to outcomes. 

The intent is that once the mapping is determined, it can be used in a clinical setting to map a particular patient's attributes to the most likely outcome. In effect, to improve the diagnoses of clinical conditions.

The machine learning process is to take an actual clinical data set (typically a large one) of known patient attributes and outcomes and divide it into various subsets. The solutions we provide enable us to pick the desired columns without reading the whole datasets into memory.

