# StatesImageClassification

### 1. Build a CNN model with Python and TensorFlow to classify 7 human emotional states: angry, confused, crying, happy, lonely, relaxed, sad in images. The data used is randomly obtained through Google search (Using Download all images extension).

### 2. The initial training data is as follows:

![image](https://github.com/tungheidiie/StatesImageClassification/assets/170008056/80180f94-a344-401c-a79e-34fccb6e8893)

### 3. Clean image dataset: Remove improperly formatted ('jpeg','jpg', 'bmp', 'png') and corrupted images.

### 4. Split the data into 70% train, 20% validation, 10% test.

### 5. Load data:

![image](https://github.com/tungheidiie/StatesImageClassification/assets/170008056/d309402d-ec52-46ba-b4e0-9c37d02b4464)

### 6. Split the data into 70% train, 20% validation, 10% test.

### 7. Model CNN:

![image](https://github.com/tungheidiie/StatesImageClassification/assets/170008056/d9c5795f-989f-4670-9aac-3a2c653a99b8)

### 8. A chart of accuracy and loss over 5 epochs for the training and validation sets.

![image](https://github.com/tungheidiie/StatesImageClassification/assets/170008056/da9fd419-49df-428a-be06-2cc3c2578632)

### 9. The accuracy on the training set is high, but it's low on the validation set (overfitting) because the initial data was randomized and contained many non-standard images.

### 10. Testing with the test data:

![image](https://github.com/tungheidiie/StatesImageClassification/assets/170008056/b6bf5e28-6eef-4fb4-b2f7-c8474e406379)

### 11. Testing with a image sample:

![image](https://github.com/tungheidiie/StatesImageClassification/assets/170008056/5a5a714e-be11-4762-ba4a-108569ac8610)

### 12. Results:

![image](https://github.com/tungheidiie/StatesImageClassification/assets/170008056/d63bed14-1df5-44e0-872e-b7dac09f8d68)

### 13. Save the model to a file: states_classifier.keras
