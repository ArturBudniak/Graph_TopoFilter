# Graph_TopoFilter
Abstract. Detection of incorrectly conducted failure repairs is not a
trivial task for companies manufacturing big volumes of goods. Extensive
data sets of service calls are periodically updated and subject matters ex-
perts would not be efficient in manual annotating of the data. Symptoms
described in free text form might be caused by different components - not
necessarily by the most obvious. Classes are imbalanced due to different
time to failure of particular components and thus actions taken for some
rare failures might be noted as incorrect ones. The presented problem is
similar to the problem of learning in a presence of noisy labels, which are
caused by human errors, variation of annotator to annotator perception,
faults made by annotating algorithms or by other reasons. There are
multiple techniques to prevent neural networks from overfitting to the
noisy data, but to our best knowledge none of them considers relation-
ships between classes, which is crucial in engineering systems built from
multiple components connected in a specific way. A novel approach of
selecting clean data samples in an unsupervised manner is presented in
this paper. It is based on a topological approach exploring the deep rep-
resentation of the features in the hidden space, enriched with knowledge
graphs reflecting the structure of the classes. We present the case study
of the algorithm utilized for service calls data set for home appliances.
