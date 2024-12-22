# otto-recommendation-system

## Code structure

If you wish to dive into the code, the repository naming should be straight-forward. Each function is documented.
The structure is the following :

```
src
├── data
│   ├── candidates_chris.py         # Chris' candidates utils
│   ├── candidates.py               # Theo's candidates utils
│   ├── covisitation.py             # Theo's covistation matrices
│   ├── fe.py                       # Feature engineering
│   └── preparation.py              # Data preparation utils
├── inference           
│   ├── boosting.py                 # Main file
│   └── predict.py                  # Predict function
├── model_zoo 
│   ├── __init__.py
│   ├── lgbm.py                     # LGBM Ranker kept for legacy
│   └── xgb.py                      # XGBoost classifier
├── otto_src                        
│   ├── evaluate.py                 # From the competition repo
│   ├── labels.py                   # From the competition repo
│   ├── my_split.py                 # My custom splitting functions
│   └── testset.py                  # From the competition repo
├── training           
│   └── boosting.py                 # Trains a boosting model
├── utils          
│   ├── load.py                     # Data loading utils 
│   ├── logger.py                   # Logging utils
│   ├── metrics.py                  # Metrics for the competition
│   ├── plot.py                     # Plotting utils
│   └── torch.py                    # Torch utils
│
├── fe_main.py                      # Main for feature engineering
└── params.py                       # Main parameters
``` 