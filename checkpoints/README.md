# Checkpoints

This folder contains the frozen MLP used for the final analyses in this study:

- `MLP_FRESH_RANDOM_SNR30_70_state_dict.pt` — trained network weights.
- `MLP_FRESH_RANDOM_SNR30_70_feature_standardisation.pt` — feature means and standard deviations used to standardise the 131 input measurements before inference.


Running `notebooks/02_train_final_mlp.ipynb` can also generate a new checkpoint from the synthetic training data.
