# NCCL Test Log

Here we provide more detailed logs of `nccl-test`.  

We evaluate on the Azure ND A100 v4 series. The cluster has up to 16 servers, and each server is equipped with eight Ampere A100 40GB Tensor Core GPUs. The default network capacity is that each GPU is provided with a dedicated 200 Gb/s InfiniBand connection. The interconnect network bandwidth of each server is thus 1.6 Tb/s.

Also, you can find more analysis in our paper's appendix, which includes some breakdown analysis.


## Citation

Please cite our paper if you use our data:

```bibtex
@article{echo2024,
  title={Echo: Simulating Distributed Training At Scale},
  author={Yicheng Feng, Yuetao Chen, Kaiwen Chen, Jingzong Li, Tianyuan Wu, Peng Cheng, Chuan Wu, Wei Wang, Tsung-Yi Ho, Hong Xu},
  journal={arXiv preprint arXiv:2412.12487},
  year={2024}
}
```
