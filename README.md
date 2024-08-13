# Estimating Galaxy Redshifts from Photometric Magnitudes

In this project, I implemented several types of machine learning models to estimate galactic redshifts from 6 types of magnitudes. I used data from the Galaxy Zoo project (gz2sample.csv) in this project. Sources can be found in the Jupyter Notebook file at the top. The results are listed below and in the Results section of the notebook. Please note that the clickable table of contents won't work in the browser; you will need to download the file and open it in an IDE like VSCode or Jupyter Notebook itself. 

| Model | Mean Squared Error |
| :- | :- |
| LinReg w/ G Magnitude | 0.00104 |
| QuadReg w/ G Magnitude | 0.00101 |
| 5thDeg Poly w/ G Magnitude | 0.000953 |
| Multiple LinReg (all mags) | 0.000774 |
| Default Decision Tree | 0.000921 |
| Tuned Decision Tree | 0.000583 |
| Default Random Forest | 0.000470 |
| Tuned Random Forest | 0.000464 |
| Default XGBoost | 0.000476 |
| Tuned XGBoost | 0.000479 |
| NN: 3 Hidden Layers & Adam | 0.000726 |
| NN: 3 Hidden Layers & SGD | 0.000755 |
| NN: 3 Hidden Layers & SGD w/ custom learning rate | 0.000833|
| NN: Tuned, 2 Hidden Layers, Adam | 0.000638|

