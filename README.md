# Graph Self-Attention for learning graph representation with Transformer

## Quick Start

### Prepair environment
```bash
conda env create --file environment.yaml
conda activate chemprop
```

### Prepare pretrained weight
Download pretrained weights from ```https://drive.google.com/drive/folders/1Oc3Ox0HAoJ5Hrihfp5-jFvStPIfFQAf9?usp=sharing```
and create folder ```pretrained_weight```.


## Reproduce results

Please check ```{dataset-name}.sh``` for detailed commands to reproduce the results.


## Hardware requirements

* 4 gpus (A100 with 80GiB) are required to run experiments for PCQM4M, PCQM4Mv2, PCBA and HIV.
* 1 gpu is required to run experiments for MNIST and CIFAR10.




