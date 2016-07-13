In the days of the "big data" buzz, many people build data driven applications
on clusters from the start. However, working with distributed computing is not
only pricey, but also requires a large engineering effort and removes
interactivity from the data exploration process. In this talk I will
demonstrate how to learn powerful nonlinear models on a single machine, even
with large data sets. This can be achieved using the partial_fit interface
provided by scikit-learn, that implements stochastic updates. Together with
stateless transformation of the data, such as hashing, kernel approximation and
random projections, these allow incrementally building a model without the need
to store all the data in memory, or even on disk. 
