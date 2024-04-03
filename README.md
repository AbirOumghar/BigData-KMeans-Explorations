# BigData-KMeans-Explorations

## Project Overview
This repository delves into the k-means clustering algorithm across sequential, streaming, and distributed processing paradigms. It is crafted for M2 MLDS/AMSD students as part of a Big Data course project, offering implementations that tackle the intricacies of large-scale data analysis.

## Implementation Highlights

### Sequential k-means in Python
- Generates a synthetic dataset.
- Implements k-means to classify data points with minimal memory footprint.

### Streaming k-means in Python
- Adapts k-means for data streams, enabling dynamic cluster updates.
- Mitigates the need to reprocess the entire dataset when new data arrives.

### Distributed k-means with Apache Beam
- Scales k-means to work with massive datasets beyond single-machine memory capabilities.
- Employs Apache Beam for efficient parallel processing.
