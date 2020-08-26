# ML.Net-sample
Test-ML.Net

TOC

# System 
MacOS



# Prerequisites

## Steps to install and use ML.Net 


Install Cellenza
```dotnet
$ dotnet new console
```

dotnet-new-console.png

```dotnet
dotnet add package Microsoft.ml
```

Install Microsoft
https://dotnet.microsoft.com/learn/ml-dotnet/get-started-tutorial/install : 

dotnet tool install -g mlnet


vsStudio :
https://www.ssa-data.com/blog/archive/what-is-mlnet-in-the-world-of-machine-learning/

## Create your first Application
```dotnet
$ mkdir myMLApp
$ cd myMLApp
$ dotnet new console -o consumeModelApp
````
"The dotnet command creates a new C# application of type console for you. The -o parameter creates a directory named consumeModelApp where your app is stored, and populates it with the required files." https://dotnet.microsoft.com/learn/ml-dotnet/get-started-tutorial/create


# Use Transfer Learning with ML.Net  - Tensorflow

## A) Transfer learning 
https://docs.microsoft.com/fr-fr/dotnet/machine-learning/tutorials/image-classification

https://medium.com/@Mareks_082/ml-net-machine-learning-library-from-microsoft-39d265761b34

## B) Run a pre-trained TensorFlow model
https://github.com/dotnet/machinelearning-samples/tree/master/samples/csharp/getting-started/DeepLearning_ImageClassification_TensorFlow

https://medium.com/@g_rishiraj/tensorflow-in-net-with-ml-net-show-notes-dc4b2b5db25b

https://towardsdatascience.com/introduction-to-machine-learning-in-c-with-ml-net-bf45502d8110

https://devblogs.microsoft.com/cesardelatorre/run-with-ml-net-c-code-a-tensorflow-model-exported-from-azure-cognitive-services-custom-vision/

# Great sources

IA/ML.NET : EMBARQUEZ DU MACHINE LEARNING DANS VOS APPLICATIONS .NET, Yann Bilissor, 19 sept 2018 : https://blog.cellenza.com/data/machine-learning/ia-ml-net-embarquez-du-machine-learning-dans-vos-applications-net/

Install ML.Net : https://dotnet.microsoft.com/learn/ml-dotnet/get-started-tutorial/intro

