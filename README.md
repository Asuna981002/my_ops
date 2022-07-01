# ai-operator-standard

框架版本：
* Tensorflow：2.9.0
* PyTorch：1.11.0
<!-- * MindSpore：xxx -->
<!-- * Paddle：xxx -->

| 算子             | TensorFlow                                                                                                                    | PyTorch                                                                                                                           | MindSpore | Paddle |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | --------- | ------ |
| [sgd](https://github.com/Asuna981002/my_ops/blob/main/%E7%AE%97%E5%AD%90%E6%A0%87%E5%87%86/%E6%A0%87%E5%87%86/%E4%BC%98%E5%8C%96%E5%99%A8/%E4%BC%98%E5%8C%96%E5%99%A8%E7%AE%97%E5%AD%90%E6%A0%87%E5%87%86.md#626-centeredrmsprop%E4%BC%98%E5%8C%96%E5%99%A8)              | [tf.keras.optimizers.SGD](https://tensorflow.google.cn/versions/r2.9/api_docs/python/tf/keras/optimizers/SGD)                 | [torch.optim.SGD](https://pytorch.org/docs/1.11/generated/torch.optim.SGD.html?highlight=sgd#torch.optim.SGD)                     |           |        |
| momentum         | [tf.keras.optimizers.SGD](https://tensorflow.google.cn/versions/r2.9/api_docs/python/tf/keras/optimizers/SGD)                 | [torch.optim.SGD](https://pytorch.org/docs/1.11/generated/torch.optim.SGD.html?highlight=sgd#torch.optim.SGD)                     |           |        |
| adagrad          | [tf.keras.optimizers.Adagrad](https://tensorflow.google.cn/versions/r2.9/api_docs/python/tf/keras/optimizers/Adagrad)         | [torch.optim.Adagrad](https://pytorch.org/docs/1.11/generated/torch.optim.Adagrad.html?highlight=adagrad#torch.optim.Adagrad)     |           |        |
| adadelta         | [tf.keras.optimizers.Adadelta](https://tensorflow.google.cn/versions/r2.9/api_docs/python/tf/keras/optimizers/Adadelta)       | [torch.optim.Adadelta](https://pytorch.org/docs/1.11/generated/torch.optim.Adadelta.html?highlight=adadelta#torch.optim.Adadelta) |           |        |
| rmsprop          | [tf.keras.optimizers.RMSprop](https://tensorflow.google.cn/versions/r2.9/api_docs/python/tf/keras/optimizers/RMSprop)         | [torch.optim.RMSprop](https://pytorch.org/docs/1.11/generated/torch.optim.RMSprop.html?highlight=rmspro#torch.optim.RMSprop)      |           |        |
| centered_rmsprop | [tf.raw_ops.ApplyCenteredRMSProp](https://tensorflow.google.cn/versions/r2.9/api_docs/python/tf/raw_ops/ApplyCenteredRMSProp) | /                                                                                                                                 |           |        |
| adam             | [tf.keras.optimizers.Adam](https://tensorflow.google.cn/versions/r2.9/api_docs/python/tf/keras/optimizers/Adam)               | [torch.optim.Adam](https://pytorch.org/docs/1.11/generated/torch.optim.Adam.html?highlight=adam#torch.optim.Adam)                 |           |        |
| adamax           | [tf.keras.optimizers.Adamax](https://tensorflow.google.cn/versions/r2.9/api_docs/python/tf/keras/optimizers/Adamax)           | [torch.optim.Adamax](https://pytorch.org/docs/1.11/generated/torch.optim.Adamax.html?highlight=adamax#torch.optim.Adamax)         |           |        |
