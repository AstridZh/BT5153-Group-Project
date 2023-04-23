"# BT5153-Group-Project" 

Dataset
  Surface Crack Detection from Kaggle
    https://www.kaggle.com/datasets/arunrk7/surface-crack-detection
 
Preprocessing
  1. randomly select 1000 samples
  2. train-test split
  3. ImageDataGenerator
    keras.preprocessing.image.dataframeiterator
 
Machine Learning Models
  1. Baseline CNN
    a. Model construction
    b. Training
    c. Performance evaluation
  2. VGG-16
    a. Model construction
    b. Training
    c. Performance evaluation
  3. ResNet50
    a. Model construction
    b. Training
    c. Performance evaluation
  4. Inception v3
    a. Model construction
    b. Training
    c. Performance evaluation
  5. Model comparison
  6. Hyperparameter tuning
    a. OPTUNA
      parameters = learning_rate, weight_decay, num_epochs, batch_size
      objective = val_loss
      direction = 'minimize'
    b. Performance evaluation
    c. Final model comparison

Interpretbility Analysis
  lime.lime_image.LimeImageExplainer
