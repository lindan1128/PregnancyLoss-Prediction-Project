# PregnancyLoss-Prediction-Project
The codes for the pregnancy loss prediction project

## Installation
Install the required packages
    
    $ pip install --user --requirement requirements.txt
    
## Usage
    
    Attention-based LSTM: Train and evaluate the attention-based lstm model using the time-series activity and the metadata
    # Directory: LSTM
    $ python main.py --path=Data/data.csv --epoch=100
    
    Transformers: Train and evaluate the attention-based transformers model using the time-series activity and the metadata
    # Directory: Transformers
    $ python main.py --path=Data/data.csv --epoch=100
