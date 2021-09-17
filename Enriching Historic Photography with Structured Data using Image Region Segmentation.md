---
tutorial: Week 1
date: 2021/09/17
tags: overview, annotations
---

# Enriching Historic Photography with Structured Data using Image Region Segmentation
[Enriching Historic Photography with Structured Data using Image Region Segmentatio](https://statsmaths.github.io/pdf/2020-enrich-photography.pdf)

  In this article, Arnold and Tilton describe different context matching techniques that they have tried to see what the best outcomes are in the automated process of matching. They looked at object detection, automated captions, image embedding and image segmentation. From my understanding, it seemed that the more generalized the object or scenario was, the easier it was to detect, for example the sky is easier to detect than a dog because there is only one sky, where as there are hundreds of dog types. While giving statistics of what worked and what didn't I couldn't help but notice that the images used were all colourized photos. What would happen if they used these techniques on black and white photos? Would the results be worse? Would it even work? I wonder if the matching algorithm also has a colour component where, to detect something like a brick building, it would pick up the red colour of bricks along with the general shape and pattern. My take away from this article however remains strict that we cannot rely on automated processes and computer algorithms when it comes to creating accessible collections online as it often makes mistakes. While efficiency is key in some respects, accuracy is more important.
  
  tags: #overview #generalidea
  
  ## Source
  
  >Most computer vision algorithmsare built using modern datasets, and may produce annota-tions that are inaccurate or inappropriate for historic data

This is an extremely important point. In my own research on automated processes for 3D digitization and 3D printing, the machine will never be able to create perfect models and it will always require some sort of human intervention to fine tune, or clean any discrepancies. For example, when you insert an image into word and want to remove the background, the computer automatically selects what it considers the background, but also takes away half of your subject, which then prompts the user to "mark areas to delete/keep". There are things that the human eye sees and knows that a computer cannot.

## Source

>For example, a re-cent study showed that face detection algorithms have dif-ficulty identifying darker skinned individuals (Buolamwiniand Gebru, 2018). Applying state-of-the-art face detectionalgorithms to a collection of photographs, therefore, risksfurther hiding marginalized communities

Interesting point. In the other article by Arnold, it mentioned that the neural network was trained in recognizing colorized images and that the results could change because of the black and white photographs. I wonder if that same neural network "problem" applies to recognizing the color of peoples skin.

## Source


>When considering historical or more diverse datasets, thecoverage is even worse

I wonder if this has to do with the quality of the images?

## Source

>Captions generated through neural networks with thehelp of linked textual data have shown to be fairly accurate

I disagree with this statement to a degree. Although Word is not the most scientific program, when an image is added it generates a suggested caption. I do get a good laugh at some of them, for example when uploading an image of the Watson's Mill plush toy mouse the caption comes out as "weird cat with a bow".

## Source

>The objectannotations do offer many useful features, but have an errorrate around 30%, making them difficult to use without man-ual validation.

I wonder if this study uses the combination of computer and human analysis where the computer finds "like objects" and say has 10 pictures of a mouse and 20 of a cat, would the human then be able to delete the pictures of the mouse to give a more accurate matching system?