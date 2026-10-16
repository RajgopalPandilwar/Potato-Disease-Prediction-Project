# Plant Disease Detection (Potato Disease Prediction)

Potato Disease Prediction Project with Code, Documents and Video Explanation.

**Author:** Rajgopal Pandilwar  

### Youtube Implementation Video : https://youtu.be/VPW8OGHTUrk

![Screenshot 2022-12-29 at 4 26 18](https://user-images.githubusercontent.com/28294942/209942633-fd0568ff-5609-4a59-866f-21d200b3e3c2.png)

---

### Abstract 

Agriculture is the cultivation of land and raising of crops to produce food. It is a form of subsistence farming that has been practised for thousands of years. With the advancement in technology and the use of artificial intelligence in diagnosing plant diseases, it becomes important to make pertinent research toward sustainable agricultural development. In the past, diagnosis of plant diseases was done by observing the symptoms of a diseased plant. However, with the advent of artificial intelligence and its application to agriculture, it has become important to make pertinent research in this area. With the use of image processing and deep learning algorithms, it is now possible to diagnose a plant disease by using a picture taken from a smartphone. The advancement of agricultural technology has made it possible to grow more crops with limited resources. Potato is one of the staple foods that are widely consumed, becoming the 4th staple food consumed throughout the world. Also, the world demand for potato is increasing significantly, primarily due to the world pandemic coronavirus. However, potato diseases are the leading cause of the decline in the quality and quantity of the harvest. Inappropriate classification and late detection of the disease's type will drastically worsen the plant conditions. Fortunately, several diseases in potato plants can be identified based on leaf conditions. However, the increase in the population of the world is constantly increasing the demand for more food. One way to meet this demand is to use artificial intelligence in diagnosing plant diseases and using that information to more efficiently grow food. Machine Learning and Deep Learning are applied for the work done.

---

## Features

- Detects potato plant diseases from leaf images using deep learning
- Classifies images into categories: Early Blight, Late Blight, Healthy
- Uses Convolutional Neural Networks (CNN) for image classification
- Can be extended to other plant disease detection tasks

## Tech Stack

- **Deep Learning** - Convolutional Neural Networks (CNN)
- **Framework** - TensorFlow / Keras
- **Language** - Python
- **Dataset** - Potato leaf images (Early Blight, Late Blight, Healthy)

## How to Run

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Place dataset in the `dataset/` directory
4. Run training: `python main.py`
5. Use the trained model for prediction on new images

## Project Structure

```
├── dataset/               # Training and validation image datasets
├── models/                # Saved model weights
├── main.py                # Training and prediction script
├── README.md              # Project documentation
```

## Credits

- Modified and maintained by **Rajgopal Pandilwar**
