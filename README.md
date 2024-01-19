####  INSTALLATION AND SETTING UP OF THE ENVIRONMENT

1. pip install accelerate -U
2. pip install transformers
3. pip install datasets

### ABOUT THE REPO
This repo splits a single custom dataset, splits into training, testing, and validation before invoking a pre-trained model from the hugging face library specifically the distilroberta-base-climate-f as the base model.

The pre-trained model is then fine-tuned for a specific downstream task to perform climate-specific classification specifically emissions classification.

### PERFORMANCE METRICS

After fine-tuning, the model was then evaluated to get its performance metrics i.e. accuracy, precision, f1 score and recall

### RE-USING THE MODEL

Once we had the model, it was then invoked to be used in a binary text classification on a different custom dataset which is totally different from the first dataset that was used.

### VIEWING THE CODE:

To view the code, click on the file "MLM_WAYNE_HUGG.ipynb"
