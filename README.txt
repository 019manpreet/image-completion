- This project is focused on implementing the task of image completion.
- We work on the dataset of handwritten digits.
- Each image is a 28 by 28 binary image.
- The dataset is added along with the code for this
- You need to include all the files in the directory to see the output results.
- In the file image-completion.py, we implement the process of image completion based on 2 methods.
- The first method uses labels of digits to generate the model for each digit.
- The second method uses the technique of Expextation-Maximization to generate the model.
- It is highly recommended to go through the theory of these methods to completely understand the code.
- The output contains completed images based on whatever model you prefer to run.
- Two methods are run functions: train_from_labels or train_with_em.
- Notaions:
	N -> number of training cases
	D -> dimensions of each vector
	K -> number of components 