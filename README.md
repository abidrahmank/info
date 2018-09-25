# Caffe Benchmarks

**Command** : `caffe train --phase TRAIN --model train_val.prototxt --iterations 100 --gpu 0`

| Device | CUDA | cuDNN | Network | batchSize | Forward  | Backward | Total (ms) |
| ------ | ---- | ----- | ------- | --------- | -------- | -------- | ---------- |
| Intel(R) Xeon(R) CPU E3-1535M v5 @ 2.90GHz  | 8.0 | 5.1 | CIFAR-10 Quick | 100 | 143.23 | 149.89 | 293.22 |
| Quadro M2000M | 8.0 | 5.1 | CIFAR-10 Quick | 100 | 5.11 | 9.46 | 14.64 | 
| Quadro M2000M | 8.0 | 6.0 | CIFAR-10 Quick | 100 | 5.19 | 9.75 | 15.03 | 

## Caffe 1.0 with & without cuDNN
**OS** : Ubuntu 16.04.5
**CPU** : Intel(R) Xeon(R) Silver 4110 CPU @ 2.10GHz
**GPU** : Quadro P2000, 5 GB
**CUDA** : v9.2
**cuDNN** : v7.2
**NVIDIA Driver** : 396.37
