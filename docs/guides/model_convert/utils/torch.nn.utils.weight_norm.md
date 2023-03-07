## torch.nn.utils.weight_norm
### [torch.nn.utils.weight_norm](https://pytorch.org/docs/stable/generated/torch.nn.utils.weight_norm.html?highlight=nn+utils+weight_norm#torch.nn.utils.weight_norm)

```python
torch.nn.utils.weight_norm(module,
                            name='weight',
                            dim=0)
```

### [paddle.nn.utils.weight_norm](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/nn/utils/weight_norm_cn.html#weight-norm)

```python
paddle.nn.utils.weight_norm(layer,
                            name='weight',
                            dim=0)
```
### 参数差异
| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| module        | layer        | 要添加权重归一化的层。                                    |