[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vYQ4W4rf)
# MiniTorch Module 3

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module3.html


You will need to modify `tensor_functions.py` slightly in this assignment.

* Tests:

```
python run_tests.py
```

* Note:

Several of the tests for this assignment will only run if you are on a GPU machine and will not
run on github's test infrastructure. Please follow the instructions to setup up a colab machine
to run these tests.

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/tensor_data.py minitorch/tensor_functions.py minitorch/tensor_ops.py minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/module.py project/run_manual.py project/run_scalar.py project/run_tensor.py

# Diagnostics output for 3.1

## Map
<img src="map.png">

## Zip
<img src="zip.png">

## Reduce
<img src="reduce.png">

# Diagnostics output for 3.2
<img src="matmul1.png">
<img src="matmul2.png">

# Graph for 3.4
<img src="data_3_4.png">
<img src="graph_3_4.png">


# Training Result for 3.5

## Simple Dataset

### HIDDEN: 100, RATE: 0.05, EPOCH: 100

#### CPU
<img src="simple_cpu_small_1.png">

#### GPU
<img src="simple_gpu_small_1.png">
<img src="simple_gpu_small_2.png">
<img src="simple_gpu_small_3.png">

## Split Dataset

### HIDDEN: 100, RATE: 0.1, EPOCH: 100

#### CPU
<img src="split_cpu_small_1.png">

#### GPU
<img src="split_gpu_small_1.png">
<img src="split_gpu_small_2.png">
<img src="split_gpu_small_3.png">

## XOR Dataset

### HIDDEN: 100, RATE: 0.5, EPOCH: 150

#### CPU
<img src="xor_cpu_small_1.png">
<img src="xor_cpu_small_2.png">

#### GPU
<img src="xor_gpu_small_1.png">
<img src="xor_gpu_small_2.png">
<img src="xor_gpu_small_3.png">
<img src="xor_gpu_small_4.png">

## Large Model with 200 Hidden

### Simple Hidden: 200, RATE: 0.05, EPOCH: 150

#### CPU
<img src="simple_cpu_large_1.png">
<img src="simple_cpu_large_2.png">

#### GPU
<img src="simple_gpu_large_1.png">
<img src="simple_gpu_large_2.png">
<img src="simple_gpu_large_3.png">
<img src="simple_gpu_large_4.png">