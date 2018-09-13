# Topic modelling on Instagram hashtags: An alternative way to Automatic Image Annotation?

### Extract topics from Instagram hashtags

We analyze a list of supervised instagram images using Latent Dirichlet allocation (LDA)—crowdflower users tagged photos based on a list of predefined hashtags. The Gensim library is used to perform the LDA analysis—this provides a number of key words for each of the 20 topics (e.g: photos with airoplanes, horses, cars etc) considered. From here, custom functions are implemented in order to analyse the prevalence of key words within a post's hashtags

*The entire analysis was done by using a Jupyter Notebook and Python 3.5.*

## Abstract

Abstract—Automatic Image Annotation (AIA) is the process of assigning tags to digital images without the intervention of humans. Most of the modern automatic image annotation methods are based on the learning by example paradigm. In those methods building the training examples, that is, pairs of images and related tags, is the first critical step. We have shown in our previous studies that hashtags accompanying images in social media and especially the Instagram provide a reach source for creating training sets for AIA. However, we concluded that only 20% of the Instagram hashtags describe the actual content of the image they accompany, thus, a series of filtering steps need to apply in order to identify the appropriate hashtags. 

In this paper we apply topic modelling with Latent Dirichlet Allocation (LDA) on Instagram hashtags in order to predict the subject of the related images. Since a topic is composed by a set of related terms, the identification of the visual topic of an Instagram image, through the proposed method, provides a plausible set of tags to be used in the context of training AIA methods.

### Prerequisites

What things you need to install the software and how to install them-

```
Jupyter notebook, Python 3+
```

## Built With

* Jupyter notebook, python, NLTK, spacy, gensim etc

## Authors

* Argyris Argyrou, 
* Stamatios Giannoulakis,
* Nicolas Tsapatsoulis,

## License

Dept. of Communication and Internet Studies Cyprus University of Technology, Limassol, Cyprus

## Acknowledgments

* All ref., included in the paper
