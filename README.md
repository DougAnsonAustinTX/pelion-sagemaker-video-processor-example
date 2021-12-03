# Pelion SageMaker Notebook Example - Video Processor

This repo contains an example Jupyter notebook with an example whereby a Data Scientist can connect a video camera to their Pelion-enabled gateway and do live predictions on the images it captures. 

The notebook  will utilize Pelion Edge as the Sagemaker Edge Agent endpoint for running the compiled models on NVidia Jetson NX Xavier. 

### Installation

1). copy all contents of this repo into your Sagemaker notebook

2). Select a Tensorflow 2.1/Python 3.6 CPU kernel and launch it

3). Before continuing, you must also have setup:

	a). Pelion Edge Running on NVidia Xavier (https://github.com/PelionIoT/XavierPelionEdge)
	b). Install https://github.com/DougAnsonAtARM/SageMakerEdgeAgentContainer on your Xavier
			b1). You will need to configure the AWS credentials for 
			     pelion-sagemaker-controller per instructions above
	c). Create an Application Key in your Pelion account 
	d). Note the Pelion Device ID for your Xavier Edge Gateway in Pelion

Both c) and d) will be used to configure some of the notebook initially... 
