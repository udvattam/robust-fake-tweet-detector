# Robust fake tweet detector

Nowadays social media, especially Twitter, is one of the battlegrounds for political confrontations. Although a majority of people involved in these discussions are using Twitter to legitimately express their opinions and support their positions, there are also users who deliberately post fake news and spread misinformation to undermine political opposition. This phenomenon has reached a point where fake tweet detection tools are being developed to tag such posts.

Fake tweet detection tools are generally data-driven, and trained by showing positive and negative examples of fake tweets to a machine learning model that learns patterns in the data. In other domains like computer vision, it has been shown that such machine learning models are vulnerable to adversarial attacks and can be easily fooled by adding the right kind of perturbations to the examples that are presented to the model. This project investigates if machine learning models used for fake tweet detection are also vulnerable to such adversarial attacks.

For more information, refer to ["adversarial_learning_for_microblogs.pdf"](https://github.com/udvattam/robust-fake-tweet-detector/blob/master/adversarial_learning_for_microblogs.pdf)
