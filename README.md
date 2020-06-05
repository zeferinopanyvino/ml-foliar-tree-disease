# ML-foliar-tree-disease
Intro to CNN with images
This project is intented to take a shot at a Kaggle competition about foliar diseases on apple trees.
Parapraph of project description
We have a dataset of around 2500 high resolution pictures (for train and another 2400 for tests) of apple leaves that may be either healthy, have rust of scam or a mixture of these diseases. 
## Getting Started
The idea of the project was to take a first glance of CNN in classification models.
This repo pretends to show what I dived on my final project of an Ironhack Bootcamp in Data Analytics. All the topics were new to me and had to dive on my own to pursue some attempt to participate in a Kaggle competition. Basically, it´s me trying to get some experience.

### Prerequisites
Know about use of Pandas, use of DataFrames, ML. To learn about the AI needed the Coursera MOOCs of Andrew Ng were super useful.
What things you need to install the software and how to install them
libraries:
*fastai 

## Running the tests

I executed the code directly on my Jupyter Notebook.

Explanation for testing:
Testing with uploaded images. For deep learning techniques I could rotate the images to generate new ones due to a very small 
image sample (2400 pics) for test and train sets.

We could generate more images rotating the images and saving them like that.


## Results

Submission should be done on the Kaggle competition section. At the end the competition ended one week later after my bootcamp.
Unfortunately I couldn`t submmit a final project. I finished learning that what was needed for this project was a lot of computing power and more time to learn about Fine-grained image recognition. Thus deep learning was needed due to 1254x1254x3 imput data before all the convolution and filtering process would have eventually got me to overfitting of the model. I needed a database of nos thousands of HR images but much more. That is a very good lesson to keep in mind for further initiatives of mine. I will keep on this project once I can enter a computing lab on further research enterprises. 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* OpenCV Python Tutorials ~ by OpenCV
* Plant Pathology: Very Concise TPU EfficientNet ~ by xhulu
* Plotly Express in Python ~ by Plotly
* EDA - Plant Pathology 2020 ~ by Peter
* Fork of Plant 2020 TPU 915e9c ~ by Alexander

## References

* Semarnat

* [Semarnat csv](https://datos.gob.mx/busca/dataset/indicadores-de-crecimiento-verde--capital-natural/resource/06ebfb05-23c5-4f75-8068-2860ec8574f3)
* [más de especies útiles](https://cienciasagricolas.inifap.gob.mx/index.php/v10n1-010)

* https://datos.gob.mx/busca/dataset/indicadores-de-crecimiento-verde--capital-natural/resource/5500f73b-7a51-4419-96ca-2a65f49b18b6

* https://datos.gob.mx/busca/dataset/indicadores-de-crecimiento-verde--capital-natural/resource/e082f9b6-0ca6-4ca6-abbd-a3b9ae9a30cc

* Conafor:

* http://transparencia01.cnf.gob.mx/OpenData/Inventario/INFyS_2009_2014/

About the model:
* [CNN](https://www.edureka.co/blog/convolutional-neural-network/)
* [FG problems](https://paperswithcode.com/task/fine-grained-image-classification)

Other ways to do it:
* [using TPU](https://www.kaggle.com/biruk1230/tpu-ensemble-effnb7-effnb6-inceptresnetv2-etc)
