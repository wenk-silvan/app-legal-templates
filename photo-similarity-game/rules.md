# Rules of Photo Similarity Game
The game is simple. Shoot a photo to match the given picture as best as possible and get the highest similarity score.

Enjoy!

## Offline Mode
Oops, no internet? Nevermind, the app will give you the option to upload a picture from your gallery which then you can match with a new photo.
You can also force offline mode in the settings even though you are connected to the internet.

## Similarity Score
To calculate the similarity score the app uses [Google's MLKit](https://developers.google.com/ml-kit/vision/image-labeling?hl=de) to label the image with recognized objects.
The more objects that were found in both pictures, the higher. So if no labels match, the score is 0 - if all labels from the taken photo are also detected in the given picture, the score is 100.

## Contact
- Email: silvan.wenk@gmail.com
- Github: https://github.com/wenk-silvan
