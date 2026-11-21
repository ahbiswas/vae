# Variational Autoencoders (VAE): Semester 3 Assignments

Three assignments on VAEs, implemented in PyTorch.

| Notebook | Dataset | Content |
|---|---|---|
| `VAE_A1_Mathematical_Implementation.ipynb` | MNIST | Architecture diagram, ELBO derivation, reparameterisation trick, worked numerical examples, effect of latent dimension (2/5/10/20) |
| `VAE_A2_Real_World_Dataset_FashionMNIST.ipynb` | Fashion-MNIST | Convolutional VAE, loss curves, reconstructions, latent space (PCA / t-SNE), interpolation, generated-sample quality evaluation |
| `VAE_A3_Beta_VAE_Comparative_Study.ipynb` | MNIST | Standard VAE vs β-VAE (β = 1, 2, 4, 8), latent traversals, disentanglement metrics, applications and limitations vs GANs |

Training uses only a few epochs (3–5) to demonstrate the full process.

**Run:** `pip install torch torchvision scikit-learn matplotlib seaborn pandas`. The datasets are downloaded automatically by torchvision.
