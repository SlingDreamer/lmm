# The source code of our LMMs
This code is developed based on the classic CBOW model, and it is avaiable at https://github.com/dav/word2vec

##Preprocessing

Firstly, preprocessing your traning corpus and generating the vocabulary of your corpus.

Secondly, performing an unsupervised morpheme segmentation using Morefessor (http://morpho.aalto.fi/projects/morpho/) for the vocabularies.

Then, executing matching between the segmentation results and the morphological compositions in the lookup tables, which can be found in the "../dataset" directory.

Finally replaceing the morphemes with their latent meanings.

##Training

use make to compile lmm-a.c lmm-s.c and lmm-m.c

run the script train_word_embedding.sh to training word embeddings.