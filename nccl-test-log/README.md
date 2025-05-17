# NCCL Test Log

Here we provide more detailed logs of `nccl-test`.  

We evaluate on the Azure ND A100 v4 series. The cluster has up to 16 servers, and each server is equipped with eight Ampere A100 40GB Tensor Core GPUs. The default network capacity is that each GPU is provided with a dedicated 200 Gb/s InfiniBand connection. The interconnect network bandwidth of each server is thus 1.6 Tb/s.

Also, you can find more analysis in our paper's appendix, which includes some breakdown analysis.
