# Grok-1

This repository contains JAX example code for loading and running the Grok-1 open-weights model.

这个仓库包含加载和运行 Grok-1 模型的示例代码

Make sure to download the checkpoint and place `ckpt-0` directory in `checkpoint`.
Then, run

确保已经下载'ckpt-0'模型，并放在'checkpoint'文件夹内，如果没有下载程序将不能运行

```shell
pip install -r requirements.txt
python run.py
```

to test the code.

测试代码

The script loads the checkpoint and samples from the model on a test input.

该脚本在测试输入上加载检查点和模型中的样本

Due to the large size of the model (314B parameters), a machine with enough GPU memory is required to test the model with the example code.
The implementation of the MoE layer in this repository is not efficient. The implementation was chosen to avoid the need for custom kernels to validate the correctness of the model.

由于模型较大（3140亿个参数），因此需要具有足够 GPU 内存的计算机才能使用示例代码测试模型。 此存储库中 MoE 层的实现效率不高。选择该实现是为了避免需要自定义内核来验证模型的正确性。
# Downloading the weights（下载模型）


You can download the weights using a torrent client and this magnet link:

您可以使用 torrent 、迅雷来下载磁力链接：

```
magnet:?xt=urn:btih:5f96d43576e3d386c9ba65b883210a393b68210e&tr=https%3A%2F%2Facademictorrents.com%2Fannounce.php&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce
```

# License

The code and associated Grok-1 weights in this release are licensed under the
Apache 2.0 license. The license only applies to the source files in this
repository and the model weights of Grok-1.

此版本中的代码和相关的 Grok-1 遵循 Apache 2.0 许可证。该许可证仅适用于此存储库和 Grok-1的模型。
