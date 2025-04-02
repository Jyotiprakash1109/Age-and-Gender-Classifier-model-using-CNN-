  UTK Face Age & Gender Prediction Model

### Overview
This deep learning model processes images from the **UTK Face dataset** to predict **age and gender**. It uses CNN architectures built with TensorFlow/Keras.

### Features
- Detects **age** and **gender** from facial images.
- Utilizes **Convolutional Neural Networks (CNNs)** for high accuracy.
- Uses **Seaborn and Matplotlib** for data visualization.
- Compatible with large-scale image datasets.

### Technologies Used
- **TensorFlow/Keras** (Deep Learning)
- **Pandas & NumPy** (Data Processing)
- **Matplotlib & Seaborn** (Visualization)
- **TQDM** (Progress tracking)

### How to Run
1. Install dependencies:  
   ```sh
   pip install tensorflow keras pandas numpy matplotlib seaborn tqdm
   ```
2. Update the dataset path in the script:
   ```python
   BASE_DIR = 'path_to_your_UTKFace_dataset'
   ```
3. Run the training script:
   ```sh
   python train_model.py
   ```

### Sample Predictions
After training, the model can predict age and gender for new images:
```python
pred_age, pred_gender = predict_image('sample_face.jpg')
print(f'Predicted Age: {pred_age}, Gender: {"Male" if pred_gender == 1 else "Female"}')
```

---

## License
This project is open-source under the MIT License.

---

## Contributors
 Jyoti Prakash (Machine Learning & NLP Enthusiast)

Feel free to contribute and enhance this project!


