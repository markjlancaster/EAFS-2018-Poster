# EAFS-2018-Poster

This is my E-Poster that is part of the EAFS 2018 Conference in Lyon, France.

The main goals are:
1)  Convert images (Farsi signatures from the UTSig database) into a format suitable for information retrieval tasks.

2)  Model the structure of the handwriting by the writer using a bag-of-words model called Latent Dirichlet Allocation (LDA).
    There are 27 genuine signatures per writer, so hopefully the natural variation has been captured by this sampling.
    
3)  Find appropriate query metrics so that the nearest image to a query (questioned signature) can be found in the UTSig database.
    This is a closed-set problem, as there are 100+ writers and we are only searching within that dataset.
