# Multi-Label Classification of Tweets with Optimized Convolution Neural Network using Binary Particle Swarm Optimization Algorithm

Pre-trained word embeddings for Skip-gram and FastText : (download from the link)
https://drive.google.com/drive/folders/1B46IpYDpfRLQtI_7TAjNwo3rZko6GiXb


The objective of this project is to classify given tweets into various categories and to detect the most relevant class of the given tweet. The classification can be based on categories or emotions of public.

For the sake of simplicity, we say a tweet contains keywords of health if it has some name of medicine or disease associated with it then we decide that tweet to be a health related tweet. So, the task is to classify tweets based on the keywords in the tweet.

CNNs have aplarge number of parameters and they can produce different classification accuracy for the same tasks based on diverse parameters including input window size, filter size, number of layers and number of neurons. The impact of these parameters on CNN accuracy in classification is first studied and optimised using an optimisation algorithm called binary particle swarm optimisation. 

A Particle Swarm Optimisation optimises the problem by iteratively trying to improve a candidate solution with regard to a given measure of quality. Here this optimisation method is used to optimize the parameters of the convolution network for achieving a better classification accuracy.

PSO is not preferable to use as optimization for a discrete-valued search spaces, so to operate on the binary search spaces, because real-valued domains can be transformed into the binary-valued domains. 

Thus the classification CNN model is optimised to give good results using  Binary Particle Swarcm algorthim that check for each possible values of every hyper parameter that we chose to optimize.
