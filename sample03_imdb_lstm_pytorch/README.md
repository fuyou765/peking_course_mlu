
# imdb lstm 分类实验

## 执行命令：
```
python  ex1_imdb_lstm_torch.py
```
训练5 epoch, 耗时约1min，训练分类精度为 0.911

## 参考结果如下：
```log
vocab_size:  20001
ImdbNet(
  (embedding): Embedding(20001, 64)
  (lstm): LSTM(64, 64)
  (linear1): Linear(in_features=64, out_features=64, bias=True)
  (act1): ReLU()
  (linear2): Linear(in_features=64, out_features=2, bias=True)
)
[2023-3-28 19:21:25] [CNNL] [Warning]:[cnnlClip] is deprecated and will be removed in the future release, please use [cnnlClip_v2] instead.
Train Epoch: 1 Loss: 0.647011    Acc: 0.607628
Train Epoch: 2 Loss: 0.425264    Acc: 0.805711
Train Epoch: 3 Loss: 0.326165    Acc: 0.863518
Train Epoch: 4 Loss: 0.269143    Acc: 0.892722
Train Epoch: 5 Loss: 0.226521    Acc: 0.912790
```
