"# BT5153-Group-Project" 

Dataset
  Surface Crack Detection from Kaggle - https://www.kaggle.com/datasets/arunrk7/surface-crack-detection
 
Preprocessing
  1. randomly select 1000 samples
  2. train-test split
  3. ImageDataGenerator - keras.preprocessing.image.dataframeiterator
 
Machine Learning Models
  1. Baseline CNN - model construction, training, performance evaluation
  2. VGG-16 - model construction, training, performance evaluation
  3. ResNet50 - model construction, training, performance evaluation
  4. Inception v3 - model construction, training, performance evaluation
  5. Model comparison
  6. Hyperparameter tuning - OPTUNA, performance evaluation, final model comparison
      
      parameters = learning_rate, weight_decay, num_epochs, batch_size
      objective = val_loss
      direction = 'minimize'

Interpretbility Analysis - lime.lime_image.LimeImageExplainer
