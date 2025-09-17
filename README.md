# CUDA Learning

这是我学习 CUDA 的记录和代码仓库。  
目标：掌握 GPU 并行编程，熟悉 CUDA API，并完成一些小型项目。

## 内容
- `notes/` 学习笔记
- `examples/` 示例代码
- `projects/` 小型项目
- `resources/` 学习资源

## 环境
- CUDA 12.6
- GPU: NVIDIA RTX 3060
- 编译: `nvcc`

## 运行示例
```bash
cd examples/vector_add
nvcc vector_add.cu -o vector_add
./vector_add
