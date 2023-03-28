基于MLU370的lstm 文本生成示例程序

### 训练 && 验证 
- 运行(模型开始训练并会对给出的一句话进行后续文本生成)
```
bash train.sh
```
- 结果
```
{'epoch': 499, 'batch': 0, 'loss': 0.0061555420979857445}
{'epoch': 499, 'batch': 1, 'loss': 0.006926478818058968}
{'epoch': 499, 'batch': 2, 'loss': 0.009385029785335064}
{'epoch': 499, 'batch': 3, 'loss': 0.011870420537889004}
{'epoch': 499, 'batch': 4, 'loss': 0.00946241244673729}
{'epoch': 499, 'batch': 5, 'loss': 0.01740102842450142}
{'epoch': 499, 'batch': 6, 'loss': 0.034948576241731644}
{'epoch': 499, 'batch': 7, 'loss': 0.008860649541020393}
{'epoch': 499, 'batch': 8, 'loss': 0.03309433534741402}
{'epoch': 499, 'batch': 9, 'loss': 0.00973115861415863}
{'epoch': 499, 'batch': 10, 'loss': 0.01133493147790432}
{'epoch': 499, 'batch': 11, 'loss': 0.006598499603569508}
{'epoch': 499, 'batch': 12, 'loss': 0.007118737790733576}
{'epoch': 499, 'batch': 13, 'loss': 0.011532913893461227}
{'epoch': 499, 'batch': 14, 'loss': 0.008232745341956615}
{'epoch': 499, 'batch': 15, 'loss': 0.019138220697641373}
{'epoch': 499, 'batch': 16, 'loss': 0.01702909916639328}
{'epoch': 499, 'batch': 17, 'loss': 0.008753176778554916}
{'epoch': 499, 'batch': 18, 'loss': 0.013557717204093933}
{'epoch': 499, 'batch': 19, 'loss': 0.011303206905722618}
{'epoch': 499, 'batch': 20, 'loss': 0.01622425764799118}
{'epoch': 499, 'batch': 21, 'loss': 0.015285501256585121}
{'epoch': 499, 'batch': 22, 'loss': 0.009379144757986069}
{'epoch': 499, 'batch': 23, 'loss': 0.02811001054942608}
{'epoch': 499, 'batch': 24, 'loss': 0.014393591322004795}
{'epoch': 499, 'batch': 25, 'loss': 0.027462856844067574}
{'epoch': 499, 'batch': 26, 'loss': 0.021595366299152374}
{'epoch': 499, 'batch': 27, 'loss': 0.025318164378404617}
{'epoch': 499, 'batch': 28, 'loss': 0.006326653063297272}
{'epoch': 499, 'batch': 29, 'loss': 0.007146001327782869}
{'epoch': 499, 'batch': 30, 'loss': 0.020447835326194763}
{'epoch': 499, 'batch': 31, 'loss': 0.00597075279802084}
{'epoch': 499, 'batch': 32, 'loss': 0.008774826303124428}
{'epoch': 499, 'batch': 33, 'loss': 0.008487898856401443}
{'epoch': 499, 'batch': 34, 'loss': 0.01407331507652998}
{'epoch': 499, 'batch': 35, 'loss': 0.01839526556432247}
{'epoch': 499, 'batch': 36, 'loss': 0.00794618483632803}
{'epoch': 499, 'batch': 37, 'loss': 0.006678356323391199}
{'epoch': 499, 'batch': 38, 'loss': 0.005798407830297947}
{'epoch': 499, 'batch': 39, 'loss': 0.004989887587726116}
{'epoch': 499, 'batch': 40, 'loss': 0.007450182922184467}
{'epoch': 499, 'batch': 41, 'loss': 0.005048778839409351}
{'epoch': 499, 'batch': 42, 'loss': 0.0023864172399044037}
#下面一行为对输入的话进行后续文本预测
['if', 'you', 'will', 'take', 'a', 'tip', 'wriggle', 'rosy', 'vexatious', 'individual', 'first', 'level', 'of', 'the', 'first', 'road', 'the', 'Avalanche', 'Creek', 'came', 'the', 'voice', 'of', 'Dad', 'Wheelis,', 'the', 'wagon-train', 'boss,', 'addressing', 'his', 'front', 'span.', 'The', 'mules', 'had', 'halted', 'at', 'the', 'head', 'of', 'the', 'steep', 'grade', 'to', 'twist', 'about', 'in', 'the', 'traces', 'and,', 'with', 'six', '’cello-shaped', 'heads', 'stretched', 'over', 'the', 'rim', 'and', 'twice', 'that', 'many', 'somber', 'eyes', 'fixed', 'on', 'the', 'abyss', 'swimming', 'in', 'a', 'green', 'haze', 'beneath', 'them,', 'to', 'contemplate', 'its', 'outspread', 'glories', 'while', 'they', 'got', 'their', 'wind', 'back.', 'It', 'became', 'evident', 'that', 'Dad', 'thought', 'the', 'breathing', 'space', 'sufficiently', 'had', 'been', 'prolonged.', 'On', 'a', 'beautiful', 'clearness', 'his', 'words', 'dropped']

```
