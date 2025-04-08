# Molecular_hackrush2025

At present everything is way too crapy. I will improve it someday hopefully if this domain interests me. 

## What are we trying to achieve and how (high level)?

Descriptor: A descriptor is a numerical feature (or a set of features) that summarizes a molecule's structure so that machine learning models can understand and use them.

Molecule (3D atoms + elements) ⟶ Descriptor (feature vector) ⟶ ML Model ⟶ Dipole moment

You’re building a model that takes the 3D structure of a molecule and predicts its dipole moment, a key molecular property related to charge distribution.

### Morgan Fingerprints (a type of 2D descriptor)
Think of them as "neighborhood hash codes" for atoms.

You look at each atom, then recursively expand the neighborhood to a certain radius (e.g., 2).

Hash those neighborhoods into bits in a binary vector (typically 1024 or 2048 long).

Binary representation of presence/absence of specific substructures.