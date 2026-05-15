# Simulation and Synthetic Data Generation of Deformable Objects
Bc. Tomáš Barančok
Supervisor: doc. RNDr. Martin Madaras, PhD.

In this project we focus on expanding a previous work regarding synthetic data generation.
The previous works focused on arbitrary non-transparent objects and transparent objects.
Our goal is to expand these works by intoducing generation of deformable transparent objects.
At the minimum we seek to propose a pipeline that takes parameters as input and outputs a realistic rendition of a conweyor belt with crushed up plastic bottles.

During the whole time  we had project seminars where we discussed the progress.

Progress:
November 2025: finished reading the relevant literature and conducted initial tests with ai generations of our models,
	       this idea was screpped as it was slow, expensive and unfit for our work

December 2025: we finilized our current pipeline and explored several possible engines for our work,
	       in this part we decided to part ways with ISAAC Sim as it was too hardware costly

Januray 2026: we learned how o operate in blender and prepared a model of a plastic bottle for later parametrization

February 2026: we finalized the bottle parametrization, allowing us to simply input scale values and color and get any desired plastic bottle

March 2026: we started experimenting with crushing physics simulation in blender,
	    first we used cloth physics which were unsucessful,
	    we then moved onto soft-body physics

April 2026: we finilezed the crushing part of the pipeline,
	    we presented parts of our work on CESCG 2026

May 2026: preparations for the Project Seminar Presentation

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

By August 2026 we want to have chosen an environment (Blender or Unreal Engine) for scattering of the objects. 
We will be conducting the generation of the final images (data) in this environment.

By December 2026 we want o have the dataset generation pipeline ready.

To test this data we could either test the similarity of individual images with reality, 
or we could create a small dataset and train some small models on it and use them for object detection on real images.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Relevant literature:
https://www.semanticscholar.org/paper/Automated-3D-Dataset-Generation-for-Arbitrary-Schulz-Hempel/83f9d58116e5f820e49c55afb37bedebf3047e74
https://davinci.fmph.uniba.sk/~kubirita1/Bachelor_Thesis.pdf (accessed on 15.5.2026)
