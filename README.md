# Thaw-Slumps-and-ML
Detecting thaw slumps using remote sensing techniques and machine learning methods.

In recent decades, Banks Island in the Northwest Territory of Canada has been marked by the 
degradation of its permafrost. A case in point is the rise in retrogressive thaw slumps (RTS), 
demonstrating the consequences of climate change in the region. Since they are inextricably 
linked to changes in the frozen ground as well as the progression of climate change on a local 
regional scale, the accurate and timely detection and observation of RTS become increasingly 
necessary. In this study, we provide an automated method for detecting RTS that utilises 
remote-sensing techniques and machine-learning methods. We developed and tested an 
algorithm based on the pixel-by-pixel classification. The training pixels contain the linear 
trends of eleven environmental indices and the short-wave band. The linear trends are derived 
from 30-m resolution imagery from Landsat 5 over a 27-year period (1984-2011), covering the 
whole of Banks Island (70028 km2
). All values of the model-performance metrics were over 
0.92, and visual inspections revealed that the forecasts are in good agreement with the ground 
truth in most situations. The results also showed that the bands “TCW”, “SAVI”, and “SWIR”
contribute the most to the model performance. The K-Nearest Neighbours (KNN) models 
detect more RTSs than the Random Forest (RF) models on average. However, the KNN models 
generate more false positives than the RF models. Out of all our models, the 12-band model 
without an additional “topographic slope” band performs best (Accuracy: 0.9879; F1-score for 
the positive label: 0.9542). The slope band improves the models with fewer bands, but its effect 
on models with many bands is detrimental. Our spatial analysis also suggests that thaw 
slumping occurs more frequently in areas where the “relict” ice type predominates. The 
surrounding topographic gradients of RTSs also suggest that slope is not a determining factor 
in their occurrence. This research enhances our capacity to localise RTS in both space and time 
and overcome the limitations of the pixel-by-pixel classification. Furthermore, it can identify 
unstable ground conditions that may lead to RTS or other thermokarst processes.
