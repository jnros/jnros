# John Rose

Systems engineer - GPU inference systems, kernel/virtualization (ex-IBM Linux)  
Focus: Inference, memory management, accelerated compute, quantization

**Selected Work**  

- 2026-04 Rootless Agent Sandbox: kernel primitives composition (ns, Landlock, seccomp) . [repo](https://github.com/jnros/agent-isolation)
- 2026-03 KV Compression (TurboQuant): memory + demand implications . [analysis](https://gist.github.com/jnros/0e3ad79e43762eb750d14c3a697543de)
- 2026-03 Paged Attention: KV cache as virtual memory (CUDA) . [repo](https://github.com/jnros/cuda-attn-ref)
- 2026-02 Decode Attention: Multi-Query, Multi-head, Group Query . [repo](https://github.com/jnros/inf-bench)
- 2026-01 Kimi K2.5: methods + systems impact . [analysis](https://gist.github.com/jnros/b198b7b78120f972b84d4787e9eb9c57)
- 2026-01 FP64 on Blackwell INT8 (Ozaki): POC . [analysis](https://gist.github.com/jnros/c97b01bff9aa683069556e6e0b6ae073) . [repo](https://github.com/jnros/slice)
- 2026-01 KV Offload (Engram): system design . [analysis](https://gist.github.com/jnros/92ed1e5b5af05d3a2fd353b4537af744)

**Linux Kernel:** Author of [rpadlpar](https://github.com/torvalds/linux/blob/v6.18/drivers/pci/hotplug/rpadlpar_core.c) (mainline PCI Hotplug) and [librtas](https://github.com/ibm-power-utilities/librtas) (POWER userspace).  

**Select Projects:** [kvm-experiments](https://github.com/jnros/kvm-experiments) Built KVM host, client VMs, and debugged passthrough / VFIO / iommu.  
[quant-sampler](https://github.com/jnros/quant-sampler) Minimal implementation of sampling in C with numerically stable softmax and custom bit-packing.  

**Background:** 7 years Linux kernel at IBM. 15 years industry. Now building inference/GPU/low-level systems.  

**Contact:** [johnrose3000@gmail.com] | [LinkedIn](https://www.linkedin.com/in/johnrose)
