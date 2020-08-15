# Pattern-Recognition

# Library

- keras
- pandas
- imgaug
- skimage
- sklearn
- scipy

## Data (Train-set)
- Normal 1357 case
- Pneumonia 3865 case

## Model

using model in the library keras (InceptionV3) to predict pneumonia and then use technique ensemble to improve accuracy.

## Result

Model average ensemble
![github](https://user-images.githubusercontent.com/42507576/90307996-e2230d80-df05-11ea-9840-bde41cfced1e.png)

Stacking ensemple
![github](https://user-images.githubusercontent.com/42507576/90308068-7e4d1480-df06-11ea-8e8d-ed6c79bb92b3.png)

Weighted average ensemble
![github](https://user-images.githubusercontent.com/42507576/90308107-d4ba5300-df06-11ea-9785-2e34bc513b12.png)

## Conclusion

Stacking ensemble : AUC score 0.975
Model Averaging ensemble : AUC score 0.960
Weighted Average ensemble : AUC score 0.960
Model weight Averaging ensemble : AUC score 0.974
