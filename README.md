# malaria_parasite

Artificial intelligence (AI) has the potential to help tackle some of the world’s most challenging problems and when coupled with popular tools and technologies for development and betterment of our society, what the point of technology when it can't help the needy and save lives. Deep learning helps us to build robust, scalable and effective solutions which can be adopted by everyone even in remote corners of the world and detection of Malaria is one of the problems which Deep learning has help to tackle.

Malaria is a life-threatening disease caused by parasites that are transmitted to people through the bites of infected female Anopheles mosquitoes. It is preventable and curable. According to WHO there are 212 Million malaria cases and 435000 deaths. Early diagnostics and treatment of malaria can prevent deaths. Malaria is prevalent across the world especially in tropical regions the severity of malaria varies based on the species of plasmodium. Symptoms are chills, fever and sweating, usually occurring a few weeks after being bitten. .

If efficent detection of malaria is made then deaths can be avoided which will ave families and communities from downward spiral of poverty. Most of the 435000 who died of Malaria were children, mainly in Africa, which is hyperendemic for malaria.when severe malaria does occur, malnourished children have a higher morbidity and mortality.when severe malaria does occur, malnourished children have a higher morbidity and mortality.when severe malaria does occur, malnourished children have a higher morbidity and mortality.

Malaria is one of the worlds deadliest diseas, and remains one of the top child killers on the planet. Malaria also keeps children from going to school, families from investing in their future, and communities from prospering, taking a huge toll on lives, livelihoods and countries’ progress.

![alt text](https://user-images.githubusercontent.com/37455387/58866717-c6ec2980-86d6-11e9-811b-d4e0a9c922c9.png)

## DIAGNOSIS:
Malaria parasites can be identified by examining under the microscope a drop of the patient’s blood, spread out as a “blood smear” on a microscope slide. Prior to examination, the specimen is stained to give the parasites a distinctive appearance. This technique remains the gold standard for laboratory confirmation of malaria. However, it depends on the quality of the reagents, of the microscope, and on the experience of the laboratorian.WHO recommends that all cases of suspected malaria be confirmed using parasite-based diagnostic testing (either microscopy or rapid diagnostic test) before administering treatment. Results of parasitological confirmation can be available in 30 minutes or less.

## CNN:
Convolution neural networks are special type of neural networks used in images recognition, images classifications and Objects detections.A convolutional neural network consists of an input and an output layer, as well as multiple hidden layers. The hidden layers of a CNN typically consist of convolutional layers, RELU layer i.e. activation function, pooling layers, fully connected layers and normalization layers.

Convolutional layer is core building block of CNN, it helps with feature detection.

Kernel K is a set of learnable filters and is small spatially compared to the image but extends through the full depth of the input image.

An easy way to understand this is if you were a detective and you are came across a large image or a picture in dark, how will you identify the image?

You will use you flashlight and scan across the entire image. This is exactly what we do in convolutional layer.

Kernel K, which is a feature detector is equivalent of the flashlight on image I, and we are trying to detect feature and create multiple feature maps to help us identify or classify the image.

We have multiple feature detector to help with things like edge detection, identifying different shapes, bends or different colors etc
![alt text](https://user-images.githubusercontent.com/37455387/58934834-3fabbe00-8789-11e9-81bf-5950375c5757.jpeg)

### TRANSFER LEARNING:
The deep learning model has been built using transfer learning on the VGG19 model.

Transfer learning is a machine learning method where a model developed for a task is reused as the starting point for a model on a second task.

It is a popular approach in deep learning where pre-trained models are used as the starting point on computer vision and natural language processing tasks given the vast compute and time resources required to develop neural network models on these problems and from the huge jumps in skill that they provide on related problems.

### vgg19 MODEL:
VGG-19 is a convolutional neural network that is 19 layers (16 convolution layers, 3 Fully connected layer, 5 MaxPool layers and 1 SoftMax layer) deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database [1]. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 224-by-224. 

ARCHITECTURE:
![alt text](https://iq.opengenus.org/content/images/2020/02/Screenshot-from-2020-02-22-16-25-15.png)

## ABOUT THE COMPETITION:
a repository of segmented cells from the thin blood smear slide images from the Malaria Screener research activity. The smartphone’s built-in camera acquired images of slides for each microscopic field of view. The images were manually annotated by an expert slide reader at the Mahidol-Oxford Tropical Medicine Research Unit in Bangkok, Thailand. The de-identified images and annotations are archived at NLM

The dataset contains a total of 25,000 cell images with instances of parasitized and uninfected cells.

LINK:--> https://www.kaggle.com/c/malaria-parasite-detection

