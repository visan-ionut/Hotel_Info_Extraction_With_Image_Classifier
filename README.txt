This code automates the collection and classification of information and
images from the official website of a hotel. Using DuckDuckGo to find the
hotel's main page, it extracts essential data such as address, description,
contact details, services, and GPS coordinates. The description is summarized
using the T5 Transformer model, and all images on the site are downloaded and
classified using a Convolutional Neural Network (CNN) model. The classified images
are then organized and stored locally based on their categories.

To meet the requirements is necessary to create an input file, an output file, and
integrating the CNN model, as well as ensuring the output contains the specified
categories (activities, conference, hotel, pool, restaurant, room, sightseeing, spa).

The purpose of this project is purely educational, to understand the process of web
scraping and image classification. It is very likely that the images may not be classified
very accurately as the training capacity of the model has been limited in terms of data.

For better accuracy, we encourage you to use the provided model and adjust its
performance (CNN structure and training dataset).

Credit: Poață Andrei Cătălin (UNSTPB, Artificial Intelligence master),
Ionuț Vișan (UNSTPB, Artificial Intelligence master)

!! We do not encourage the use of web scraping techniques that violate
the terms and conditions of websites.
