# Simulated Self-driving Cars Using CNN

## How I did it.
1. Training images were collected by driving manually in the simulated track.
2. Then new images where augmented using an augmentation engine, which altered brightness, added shadows, shifted images, and flipped images.
3. A CNN architecture was build using Keras Python.
4. The model was trained.
5. The model was tested on the simulated track.

---
## Links
- Drive with collected data: https://drive.google.com/drive/folders/1qqYwn64i4nKdcy_PMV0-THky_yjM6P-P?usp=sharing
- Video for model successfully passing track 2: https://www.youtube.com/watch?v=ulbVYExslYo
- Helpful articles:
    1.  Image augmentation: https://github.com/UjjwalSaxena/Automold--Road-Augmentation-Library
    2.  Exaplnation 1: https://towardsdatascience.com/behavioural-cloning-applied-to-self-driving-car-on-a-simulated-track-5365e1082230
    3.  Explanation 2: https://chatbotslife.com/using-augmentation-to-mimic-human-driving-496b569760a9#.5dpi87xzi
