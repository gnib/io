Bindings info for developers
============================

Welcome to the documentation site for BigML's bindings developers. We'll
try to provide the latest news and issues affecting the bindings for the BigML
REST API and associated resources.

Each binding has its own particular structure, but generally speaking, these
are the function levels they provide:

Basic functions:

- Connection client: manages the connection to BigML's servers and stores user
  credentials.

- REST API interface: manages the REST calls to BigML's API for all the
  available resources, namely:

    - Sources
    - Datasets
    - Models
    - Predictions
    - Evaluations
    - Batch Predictions
    - Ensembles
    - Clusters
    - Centroids
    - Batch Centroids

  You can learn about the properties of these resources and the API calls'
  arguments in the [developers section](https://bigml.com/developers) of
  our website.

Advanced functions:

- Advanced methods: BigML offers the ability to download datasets or batch
  predictions in a csv format. Some bindings provide methods to download
  such files.

- Local models, ensembles and clusters: BigML's predictive models can be
  downloaded as JSON structures. Bindings can provide objects built on this
  JSON which are able to produce local predictions.

- Fields utilities: Bindings can provide utilities that help listing, or
  extracting specfic field information from the corresponding attribute in each
  resource's JSON.

The Python and Node.js bindings are maintained by BigML's team and are usually
updated to offer the latest added features. They can be used as reference in
new bindings development.

Documentation and tests:

To the best interest of the bindings' users and the entire community, we highly
encourage our bindings' authors to document and test all new functions as they
are added. Code examples and use cases are especially useful to speed learning,
and good quality code needs good quality documents and tests to reach its goal.

Backend new features:

There's an [API news](https://github.com/bigmlcom/io/bindings/news.md) notice
in this report that will be updated to
show the features recently added in the API. It will also provide any
information needed to create the corresponding bindings interface. We will keep
a [historic record](https://github.com/bigmlcom/io/bindings/archive/) for the
latest new features as they are updated.