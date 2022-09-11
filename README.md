---
license: apache-2.0
tags:
- generated_from_keras_callback
model-index:
- name: prikarsartam/Olga__The-Headlineser
  results: []
---

<!-- This model card has been generated automatically according to the information Keras had access to. You should
probably proofread and complete it, then remove this comment. -->

# prikarsartam/Olga__The-Headlineser

This model is a fine-tuned version of [prikarsartam/Olga__The-Headlineser](https://huggingface.co/prikarsartam/Olga__The-Headlineser) on an unknown dataset.
It achieves the following results on the evaluation set:
- Train Loss: 2.6154
- Validation Loss: 2.4298
- Train Rouge1: 29.4609
- Train Rouge2: 8.3437
- Train Rougel: 23.0867
- Train Rougelsum: 23.0929
- Train Gen Len: 18.8153
- Epoch: 0

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- optimizer: {'name': 'AdamWeightDecay', 'learning_rate': 2e-06, 'decay': 0.0, 'beta_1': 0.9, 'beta_2': 0.999, 'epsilon': 1e-07, 'amsgrad': False, 'weight_decay_rate': 0.01}
- training_precision: float32

### Training results

| Train Loss | Validation Loss | Train Rouge1 | Train Rouge2 | Train Rougel | Train Rougelsum | Train Gen Len | Epoch |
|:----------:|:---------------:|:------------:|:------------:|:------------:|:---------------:|:-------------:|:-----:|
| 2.6154     | 2.4298          | 29.4609      | 8.3437       | 23.0867      | 23.0929         | 18.8153       | 0     |


### Framework versions

- Transformers 4.21.3
- TensorFlow 2.8.2
- Datasets 2.4.0
- Tokenizers 0.12.1
