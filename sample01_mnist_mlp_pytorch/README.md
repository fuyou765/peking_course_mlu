# 实验1

## 执行命令：
```
python ex1_activations_torch.py
```

## 参考结果如下：
```log
Z:
 tensor([[0.7000]], device='mlu:0') 
Shape torch.Size([1, 1])
Result torch sigmoid: tensor([[0.6682]], device='mlu:0')
Result act sigmoid: tensor([[0.6682]], device='mlu:0')
Result torch Tanh: tensor([[0.6044]], device='mlu:0')
Result act Tanh: tensor([[0.6044]], device='mlu:0')
Result torch LeakyReLU: tensor([[0.7000]], device='mlu:0')
Result act LeakyReLU: tensor([[0.7000]], device='mlu:0')
```


# 实验2


## 执行命令：
```
python ex2_mnist_mlp_torch.py
```
训练50 epoch, 耗时约5min,训练分类精度为 0.99
## 参考结果如下：
```
Train Epoch: 1 Loss: 0.300400   Acc: 0.912574
Train Epoch: 2 Loss: 0.154335   Acc: 0.956234
Train Epoch: 3 Loss: 0.119694   Acc: 0.966096
Train Epoch: 4 Loss: 0.113962   Acc: 0.968017
Train Epoch: 5 Loss: 0.099048   Acc: 0.972726
Train Epoch: 6 Loss: 0.089873   Acc: 0.975163
Train Epoch: 7 Loss: 0.087793   Acc: 0.975974
Train Epoch: 8 Loss: 0.091638   Acc: 0.975591
Train Epoch: 9 Loss: 0.084740   Acc: 0.976929
Train Epoch: 10 Loss: 0.068179  Acc: 0.981055
Train Epoch: 11 Loss: 0.071437  Acc: 0.980588
Train Epoch: 12 Loss: 0.065763  Acc: 0.982065
Train Epoch: 13 Loss: 0.061831  Acc: 0.983281
Train Epoch: 14 Loss: 0.063437  Acc: 0.983903
Train Epoch: 15 Loss: 0.067793  Acc: 0.982509
Train Epoch: 16 Loss: 0.060314  Acc: 0.983953
Train Epoch: 17 Loss: 0.060939  Acc: 0.983736
Train Epoch: 18 Loss: 0.056258  Acc: 0.985719
Train Epoch: 19 Loss: 0.049915  Acc: 0.986335
Train Epoch: 20 Loss: 0.056256  Acc: 0.985969
Train Epoch: 21 Loss: 0.047117  Acc: 0.987546
Train Epoch: 22 Loss: 0.057558  Acc: 0.985658
Train Epoch: 23 Loss: 0.051932  Acc: 0.986718
Train Epoch: 24 Loss: 0.052569  Acc: 0.986652
Train Epoch: 25 Loss: 0.065547  Acc: 0.985152
Train Epoch: 26 Loss: 0.048617  Acc: 0.988584
Train Epoch: 27 Loss: 0.044174  Acc: 0.989617
Train Epoch: 28 Loss: 0.050903  Acc: 0.988162
Train Epoch: 29 Loss: 0.056930  Acc: 0.987101
Train Epoch: 30 Loss: 0.046235  Acc: 0.989383
Train Epoch: 31 Loss: 0.035178  Acc: 0.990866
Train Epoch: 32 Loss: 0.040734  Acc: 0.990200
Train Epoch: 33 Loss: 0.047943  Acc: 0.988317
Train Epoch: 34 Loss: 0.049785  Acc: 0.988428
Train Epoch: 35 Loss: 0.058530  Acc: 0.987868
Train Epoch: 36 Loss: 0.045809  Acc: 0.989933
Train Epoch: 37 Loss: 0.039804  Acc: 0.990633
Train Epoch: 38 Loss: 0.029364  Acc: 0.992432
Train Epoch: 39 Loss: 0.042014  Acc: 0.990816
Train Epoch: 40 Loss: 0.067301  Acc: 0.986352
Train Epoch: 41 Loss: 0.046063  Acc: 0.990666
Train Epoch: 42 Loss: 0.035035  Acc: 0.991999
Train Epoch: 43 Loss: 0.038310  Acc: 0.991344
Train Epoch: 44 Loss: 0.042285  Acc: 0.991260
Train Epoch: 45 Loss: 0.041440  Acc: 0.991205
Train Epoch: 46 Loss: 0.038334  Acc: 0.991044
Train Epoch: 47 Loss: 0.043537  Acc: 0.990794
Train Epoch: 48 Loss: 0.032226  Acc: 0.992448
Train Epoch: 49 Loss: 0.051783  Acc: 0.990166
Train Epoch: 50 Loss: 0.070880  Acc: 0.986813
```

# 实验3
## 执行命令：
```
python ex3_by.py
```
## 参考结果如下：

```log
loss:[0.69203409] batch_acc:0.75 batch_size:4 lr:10
loss:[1.25450985] batch_acc:0.75 batch_size:4 lr:10
loss:[0.67399435] batch_acc:0.75 batch_size:4 lr:10
loss:[0.73806371] batch_acc:0.75 batch_size:4 lr:10
loss:[0.59121367] batch_acc:0.75 batch_size:4 lr:10
loss:[0.60257843] batch_acc:0.75 batch_size:4 lr:10
loss:[0.58476601] batch_acc:0.75 batch_size:4 lr:10
loss:[0.5933767] batch_acc:0.75 batch_size:4 lr:10
loss:[0.57919593] batch_acc:0.75 batch_size:4 lr:10
loss:[0.58599169] batch_acc:0.75 batch_size:4 lr:10
loss:[0.57169495] batch_acc:0.75 batch_size:4 lr:10
loss:[0.57700592] batch_acc:0.75 batch_size:4 lr:10
loss:[0.55772328] batch_acc:0.75 batch_size:4 lr:10
loss:[0.56547274] batch_acc:0.75 batch_size:4 lr:10
loss:[0.53775459] batch_acc:0.75 batch_size:4 lr:10
loss:[0.59416955] batch_acc:0.75 batch_size:4 lr:10
loss:[0.56399587] batch_acc:1.0 batch_size:4 lr:10
loss:[0.79678222] batch_acc:0.75 batch_size:4 lr:10
loss:[0.49871581] batch_acc:1.0 batch_size:4 lr:10
loss:[0.63463711] batch_acc:0.75 batch_size:4 lr:10
loss:[0.37836327] batch_acc:1.0 batch_size:4 lr:10
loss:[0.46249567] batch_acc:0.75 batch_size:4 lr:10
loss:[0.31626199] batch_acc:1.0 batch_size:4 lr:10
loss:[0.4688162] batch_acc:0.75 batch_size:4 lr:10
loss:[0.28200563] batch_acc:1.0 batch_size:4 lr:10
loss:[0.44984592] batch_acc:0.75 batch_size:4 lr:10
loss:[0.18519131] batch_acc:1.0 batch_size:4 lr:10
loss:[0.19247196] batch_acc:0.75 batch_size:4 lr:10
loss:[0.03874954] batch_acc:1.0 batch_size:4 lr:10
loss:[0.03391766] batch_acc:1.0 batch_size:4 lr:10
loss:[0.03053079] batch_acc:1.0 batch_size:4 lr:10
loss:[0.02776415] batch_acc:1.0 batch_size:4 lr:10
loss:[0.02545766] batch_acc:1.0 batch_size:4 lr:10
loss:[0.02350424] batch_acc:1.0 batch_size:4 lr:10
loss:[0.02182791] batch_acc:1.0 batch_size:4 lr:10
loss:[0.02037316] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01909847] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01797214] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01696955] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01607128] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01526179] batch_acc:1.0 batch_size:4 lr:10
loss:[0.0145285] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01386111] batch_acc:1.0 batch_size:4 lr:10
loss:[0.0132511] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01269138] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01217598] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01169984] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01125864] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01084868] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01046677] batch_acc:1.0 batch_size:4 lr:10
loss:[0.01011013] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00977634] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00946329] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00916912] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00889216] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00863097] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00838425] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00815082] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00792966] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00771982] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00752047] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00733084] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00715025] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00697807] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00681372] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00665671] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00650654] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00636278] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00622504] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00609294] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00596616] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00584438] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00572731] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00561469] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00550628] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00540183] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00530115] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00520403] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00511029] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00501976] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00493228] batch_acc:1.0 batch_size:4 lr:10
loss:[0.0048477] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00476587] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00468667] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00460998] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00453567] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00446365] batch_acc:1.0 batch_size:4 lr:10
loss:[0.0043938] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00432603] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00426026] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00419639] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00413434] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00407404] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00401542] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00395841] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00390295] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00384896] batch_acc:1.0 batch_size:4 lr:10
loss:[0.0037964] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00374521] batch_acc:1.0 batch_size:4 lr:10
loss:[0.00369534] batch_acc:1.0 batch_size:4 lr:1
```

# 实验4

## 执行命令：
```
python examples_torch.py
```
## 参考结果如下：
```log
X:
 tensor([[1., 2., 3.]]) 
Shape: torch.Size([1, 3])
W:
 tensor([[-0.5000],
        [ 0.2000],
        [ 0.1000]]) 
Shape torch.Size([3, 1])
Z:
 tensor([[0.7000]]) 
Shape torch.Size([1, 1])
X:
 tensor([[1., 2., 3.]]) 
Shape: torch.Size([1, 3])
W:
 tensor([[-0.5000, -0.3000],
        [ 0.2000,  0.4000],
        [ 0.1000,  0.1500]]) 
Shape torch.Size([3, 2])
Z:
 tensor([[0.7000, 1.3500]]) 
Shape torch.Size([1, 2])
Result torch sigmoid: tensor([[0.6682]])
Result your own sigmoid: tensor([[0.6682]])
Result torch softmax: tensor([[0.3430, 0.6570]])
Result your own softmax: tensor([[0.3430, 0.6570]])
/torch/venv3/pytorch/lib/python3.7/site-packages/torch/nn/modules/container.py:139: UserWarning: Implicit dimension choice for softmax has been deprecated. Change the call to include dim=X as an argument.
  input = module(input)
Neural network output:  torch.Size([1, 2])
Loss MAE: 1.0 
Loss MSE: 1.0
Loss MSE by torch: 1.0
Target value:[[1. 0.]]
Neural network output:[[0.423719 0.576281]]
Loss binary cross entropy:0.7629010677337646
Gradient of w is: [3.]
Gradient of the network layer 1's weights is: 
[[0.00496678 0.00993355 0.01490033]
 [0.01376176 0.02752351 0.04128527]
 [0.         0.         0.        ]]
Before optimization, network layer 1's weights is: 
[[-0.5669673   0.27330336  0.54320264]
 [ 0.33784539  0.22147375  0.25147405]
 [ 0.14897908 -0.46751714 -0.03618013]]
After optimization, network layer 1's weights is: 
[[-0.56706667  0.2731047   0.5429046 ]
 [ 0.33757016  0.22092329  0.25064835]
 [ 0.14897908 -0.46751714 -0.03618013]]
```
