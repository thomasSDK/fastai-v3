# Starter for deploying [fast.ai](https://www.fast.ai) models

This repo has been modified to run a test application to classify [nudibranchs](https://www.wikiwand.com/en/Nudibranch)

Nudibranchs also known as nudi are a group of soft-bodied, marine gastropod molluscs which shed their shells after their larval stage. They are noted for their often extraordinary colours and striking forms, and they have been given colourful nicknames to match, such as "clown," "marigold," "splendid," "dancer," "dragon," or "sea rabbit." Currently, about 3,000 valid species of nudibranchs are known.

The word "nudibranch" comes from the Latin nudus "naked" and the Ancient Greek βράγχια (bránkhia) "gills". 

The current 4 species it can classify are: 

  chromodoris lochi,  
  hermissenda crassicornis,  
  hexabranchus sanguineus,  
  nembrotha kubaryana

-----------------------------------------------------------------------

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

Other means of deployment are being tested...
