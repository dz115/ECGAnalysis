# ECGAnalysis

A hobby ECG(EKG) rhythm analysis project using SciPy, Pandas, NumPy, and Matplotlib based on Proto Bioengineering's articles on Medium: https://medium.com/@protobioengineering/heart-analysis-with-python-part-2-labeling-ekgs-with-code-a381dfd031ba

Initial labeling/analysis is done on ECG data from SciPy's built in ECG dataset, a 5 minute excerpt from the MIT-BIH Arrhythmia Database:

Moody GB, Mark RG. The impact of the MIT-BIH Arrhythmia Database. IEEE Eng in Med and Biol 20(3):45-50 (May-June 2001). (PMID: 11446209)

# Background

An electrocardiogram (ECG or EKG) captures the heart's electrical activity to assess various cardiac conditions. Sensors attached to the chest pick up electrical impulses that trigger heartbeats, and these impulses are displayed as wavy lines on a computer screen or printout. ECGs can be used to identify and diagnose many heart conditions, including abnormal heart rhythms, heart attacks, and other metabolic conditions that can affect the heart.

As a paramedic, ECG interpretation is one of the more heavily emphasized skills in my training due to its usefulness in quickly diagnosing dangerous conditions. It is also a skill that myself and many new clinicians have difficulty with because of the complexity of cardiac electrophysiology. As such, I have started this project to bridge my interests in acute care medicine with data science. 

The end goal is to develop a tool able to analyze both 12-lead ECGs and singular rhythm strips in a stepwise methodology similar to how human clinicians are trained to interpret, as opposed to current computational pattern recognition methods.

**Disclaimer: This is a project built purely for personal interest and is *not reliable enough* to be used as a substitute for actual medical professionals or human ECG interpretation!!!**
