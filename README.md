# image_reconstrcution
A novel strategy to shredded image reconstruction via Markov chain Monte Carlo method.

# Abstract
Ever since the paper shredder was invented, people have worked on retrieving the original document from the pieces. The unshredding problem can be viewed as a special case of the general jigsaw reconstruction problem. However, the majority of early methods focus entirely on the shape information of the pieces, such as the reconstruction of hand-torn documents, which are generally quite computationally expensive. In this paper, we utilize the visual information of the pieces with the focus on automatic reconstruction of cross shredded documents. As opposed to the jigsaw formulation, this problem has no edge shape information to use. We employ the Metropolis-Hastings algorithm of a Markov chain Monte Carlo method with a cost function to effectively determine the status of two pairwise shredders sequentially. The proposed method is capable of solving over 150 instances. In addition, multi-pages with various types (printed, handwriting and image) of documents can be recovered. The optimization strategy is also provided to speed the reconstruction process.  Finally, the current bottlenecks in this pipeline are identified and solutions are proposed.
