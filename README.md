# Charity application classifier

A learning project that uses a TensorFlow/Keras neural network to predict `IS_SUCCESSFUL` from charity application records. The [main notebook](AlphabetSoupCharity.ipynb) loads public course data, bins infrequent categories, encodes categorical features, scales inputs, and trains a two-hidden-layer binary classifier.

The prior saved run reported **72.3% test accuracy** after five epochs (test loss about 0.555). This is a historical notebook result, not a newly reproduced benchmark. The main notebook's loading and encoding syntax was repaired and stale cell outputs cleared on 2026-09-28; it has not been rerun against the live source.

[Main notebook](AlphabetSoupCharity.ipynb) · [Optimization exercise](AlphabetSoupCharity_Optimization.ipynb)

The older and copied notebooks are retained as historical drafts. The optimization exercise uses a local file path and needs additional work before it can run elsewhere. The project does not assess loan defaults or establish lending decisions. For a production model, category mapping and encoding should be learned on the training fold, with a baseline, threshold analysis, and monitoring plan.
