# PIRO Baseline Implementations

This repository contains reproducible implementations of several popular inverse reinforcement learning (IRL) and imitation learning baselines. These implementations are used to evaluate and compare with our proposed method, **PIRO** (formerly referred to as **TRRL**).

## 📋 Included Baselines

- **AIRL** (Adversarial Inverse Reinforcement Learning)
- **GAIL** (Generative Adversarial Imitation Learning)
- **BC** (Behavior Cloning)
- **Dagger** (Dataset Aggregation)
- **SQIL** (Soft Q Imitation Learning)
- **IQ-Learn**
- **HYPE**
- **FILTER**

Each algorithm is placed in its own directory or script with a modular training pipeline for compatibility and comparison under shared evaluation settings.


## 🚀 Running a Baseline

Each method has a corresponding training entry point. For example:

```bash
python BC.py --env HalfCheetah-v3
```


## 📁 Directory Structure (Example)

```
.
├── airl/
├── bc/
├── dagger/
├── iqlearn/
├── sqil/
├── hype/
├── filter/
├── common/              # Shared utilities
├── results/             # Logs and saved models
└── train_<algo>.py      # Entry points
```

## 📄 License

This project is released under the MIT License.

## 🙌 Acknowledgements

This repository includes or adapts components from the official implementations and open-source reimplementations of each baseline. Please refer to individual files for more detailed attributions.

