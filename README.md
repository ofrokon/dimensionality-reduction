# Dimensionality Reduction: Simplifying Complex Data

This repository contains Python scripts demonstrating various dimensionality reduction techniques, from PCA to Autoencoders. It accompanies the Medium post "Dimensionality Reduction: Simplifying Complex Data".

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Visualizations](#visualizations)
4. [Techniques Covered](#techniques-covered)
5. [Contributing](#contributing)
6. [License](#license)

## Installation

To run these scripts, you need Python 3.6 or later. Follow these steps to set up your environment:

1. Clone this repository:
   ```
   git clone https://github.com/ofrokon/dimensionality-reduction.git
   cd dimensionality-reduction
   ```

2. (Optional) Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

To generate all visualizations, run:

```
python dimensionality_reduction.py
```

This will create PNG files for each dimensionality reduction technique in the current directory.

## Visualizations

This script generates the following visualizations:

1. `pca_iris.png`: Demonstrates PCA on the Iris dataset
2. `tsne_iris.png`: Shows t-SNE applied to the Iris dataset
3. `umap_iris.png`: Illustrates UMAP dimensionality reduction
4. `autoencoder_iris.png`: Displays Autoencoder-based dimensionality reduction

## Techniques Covered

1. Principal Component Analysis (PCA)
2. t-Distributed Stochastic Neighbor Embedding (t-SNE)
3. Uniform Manifold Approximation and Projection (UMAP)
4. Autoencoder (using PyTorch)

Each technique is explained in detail in the accompanying Medium post, including:
- When to use each method
- Pros and cons
- Python implementation
- Visualization of dimensionality reduction results

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your suggested changes. If you're planning to make significant changes, please open an issue first to discuss what you would like to change.

## License

This project is open source and available under the [MIT License](LICENSE).

---

For a detailed explanation of these clustering algorithms and their applications, check out the accompanying Medium post: [Dimensionality Reduction: Simplifying Complex Data](https://medium.com/@mroko001/dimensionality-reduction-simplifying-complex-data-42d92c56ccbb)

For questions or feedback, please open an issue in this repository.
