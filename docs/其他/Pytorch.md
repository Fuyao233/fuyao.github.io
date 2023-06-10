#### 使用优化器的注意点

- `loss.backward()` 是为了得到计算图上节点的梯度
  - 注意：在计算loss过程中不要不小心截断梯度，比如使用循环从网络输出`output`中取值构建新的张量
- `optimizor.step()` 前注意清空累计梯度 `optimizor.zero_grad()`
- `optimizor` 只会更新构建时指定的模型参数



