# ML-foliar-tree-disease
Intro to CNN with images
This project is intented to take a shot at a Kaggle competition about foliar diseases on apple trees.
Parapraph of project description
We have a dataset of around 2500 high resolution pictures of apple leaves that may be either healthy, have rust of scam or a mixture of these diseases. 
## Getting Started
The idea of the project was to take a first glance of CNN in classification models.
se instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them
libraries:
*fastai :
```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why
Testing with uploaded images. For deep learning techniques i could rotate the images to generate new ones due to a very small 
image sample (1400 pics).

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

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
