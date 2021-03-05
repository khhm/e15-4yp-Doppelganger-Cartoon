---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: eYY-4yp-project-template
title: Doppelganger Cartoon
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Project Title

#### Team

- E/15/065, De Silva K.G.P.M., [e15065@eng.pdn.ac.lk](mailto:e15065@eng.pdn.ac.lk)
- E/15/076, Dileka J.H.S., [e15076@eng.pdn.ac.lk](mailto:e15076@eng.pdn.ac.lk)
- E/15/220, Maliththa K.H.H., [e15220@eng.pdn.ac.lk](mailto:e15220@eng.pdn.ac.lk)

#### Supervisors

- Dr. Asitha Bandaranayake, [asithab@pdn.ac.lk](mailto:asithab@pdn.ac.lk)
- Mr. Sampath Deegalla, [dsdeegalla@pdn.ac.lk](mailto:dsdeegalla@pdn.ac.lk)
- Mr. Ishan Gammampila

#### Table of content

1. [Abstract](#abstract)
2. [Related works](#related-works)
3. [Methodology](#methodology)
4. [Experiment Setup and Implementation](#experiment-setup-and-implementation)
5. [Results and Analysis](#results-and-analysis)
6. [Conclusion](#conclusion)
7. [Publications](#publications)
8. [Links](#links)

---

## Abstract

Human face recognition and feature extraction have been the most interesting technologies to study for many researchers. It allows a huge number of face images to be recognized in just a short amount of time and extract the face features very easily, rather than recognizing each image and it's features individually through a normal human's eyes.Using these technologies researches are being carried out to find the look-alike characters within humans. Using methods for real people, cartoon character faces can hardly be detected and recognized because the face features of cartoon characters differ greatly from those of real people in terms of size and shape. This research was conduct to find the techniques to face detection,feature extraction of a cartoon characters and recognize look-alike cartoon character for a given human image. We have created Disney cartoon repository including 800 images from 77 characters, 5 images from each character with mirror images. Also include face features marked by hand as 35 labeled coordinates. For cartoon face detection and feature extraction, landmark based model trained using feature marked dataset. Used distances and the areas between the landmarks as features. Total 92 features(50 areas and 42 distances) are stored as csv files along with the cartoon images. To compare features of a real image with all the cartoon image features euclidean distance was considered. To increase the accuracy we used landmark based model with hair extraction model and also include gender prediction model. This combined model improves the performance compared to basic landmark based model. Alternatively, we implemented a classification model to find the best matching cartoon character. It shows 84\% accuracy on training data and 80\% accuracy on validation after 100 epochs. Finally we were able to find the best matching Doppelganger Cartoon character with good accuracy. So we hope this research and the dataset created by us will be more useful to other researchers.

## Related works

## Methodology

## Experiment Setup and Implementation

## Results and Analysis

## Conclusion

## Publications
1. [Semester 7 report](./)
2. [Semester 7 slides](./)
3. [Semester 8 report](./)
4. [Semester 8 slides](./)
5. Author 1, Author 2 and Author 3 "Research paper title" (2021). [PDF](./).


## Links

[//]: # ( NOTE: EDIT THIS LINKS WITH YOUR REPO DETAILS )

- [Project Repository](https://github.com/cepdnaclk/e15-4yp-Doppelganger-Cartoon)
- [Project Page](https://cepdnaclk.github.io/e15-4yp-Doppelganger-Cartoon)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)

[//]: # "Please refer this to learn more about Markdown syntax"
[//]: # "https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet"
