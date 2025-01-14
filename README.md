# LCvsGC
**A multi-label classifier for predicting the most appropriate instrumental method for the analysis of contaminants of emerging concern**

This repository contains the scripts that were used in the publication https://www.mdpi.com/2218-1989/12/3/199

The scripts can be used to predict the ionization amenability of new substances.

**Abstract**
Liquid chromatography high-resolution mass spectrometry (LC-HRMS) and gas chromatography high-resolution mass spectrometry (GC-HRMS) have revolutionized analytical chemistry among many other disciplines. These advanced instrumentations allow to theoretically capture the whole chemical universe that is contained in samples, giving unimaginable opportunities to the scientific community. Laboratories equipped with these instruments produce a lot of data daily that can be digitally archived. Digital storage of data opens up the opportunity for retrospective suspect screening investigations for the occurrence of chemicals in the stored chromatograms. The first step of this approach involves the prediction which data is more appropriate to be searched. In this study, we built an optimized multi-label classifier for predicting the most appropriate in-strumental method (LC-HRMS or GC-HRMS or both) for the analysis of chemicals in digital specimens. The approach involved the generation of a baseline model based on knowledge that an expert would use and the generation of an optimized machine learning model. A multi-step feature selection approach, a model selection strategy, and optimization of the classifier's hyperparameters led to a model with accuracy that outperformed the baseline implementation. The models were used to predict the most appropriate instrumental technique for new substances.
