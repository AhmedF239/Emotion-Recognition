# Facial-Recognition

This application can: 

- Crop the face from the picture.
- Compute the face detection score which tells that we have detected the face correctly from the image.
- Name of the person in the picture.
- Face Name score (Analyze the name of the person based on the images on which it has trained)
- Emotion Name (Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise)
- Emotion Score (how accurately we have detected the emotion score) 
- This project can only tell the name of a few celebrities since the model is trained only on the given list of celebrities:
  - Angelina Jolie
  - Barack Obama
  - Cristiano Ronaldo
  - Donald Trump
  - Elon Musk
  - Joe Biden
  - Leonardo DiCaprio
  - Lionel Messi
  - Robert Downey Jr
  - Roger Federer
  - Scarlett Johansson
  - Tom Cruise

To run the code: 
1. Clone this repo
```
https://github.com/AhmedF239/Emotion-Recognition
```
2. cd into directory
```
cd facerecognition
```
3. Download the requirements
```
pip install -r requirements.txt
```
4. Runserver
```
python manage.py runserver
```
5. Open web browser at http://localhost:8000
