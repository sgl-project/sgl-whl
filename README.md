# SGLang Wheels Index

Select your preferences and run the install command.

## NVIDIA GPUs

```bash
# default cu128
pip3 install sglang --upgrade

# cu126
pip3 install sglang --index-url https://docs.sglang.ai/sgl-whl/cu126 --upgrade
# cu128
pip3 install sglang --index-url https://docs.sglang.ai/sgl-whl/cu128 --upgrade
# cu129
pip3 install sglang --index-url https://docs.sglang.ai/sgl-whl/cu129 --upgrade
```

## AMD ROCm GPUs

```bash
pip3 install sglang --index-url https://docs.sglang.ai/sgl-whl/rocm6.4 --upgrade
```

## Intel AMX CPU

```bash
pip3 install sglang --index-url https://docs.sglang.ai/sgl-whl/amx --upgrade
```

## Ascend NPU

```bash
pip3 install sglang --index-url https://docs.sglang.ai/sgl-whl/npu --upgrade
```

## Google TPU

```bash
pip3 install sglang --index-url https://docs.sglang.ai/sgl-whl/tpu --upgrade
```
