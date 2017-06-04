# Word2vecRec

## Setup

```
brew install pip3
pip3 install gensim
git clone https://github.com/liuslevis/Word2vecRec
cd Word2vecRec
```

## Usage

```
➜  Word2vecRec git:(master) ✗ python3 train.py
choose:
     0
     1 霍乱时期的爱情
     2 活着
     3 创业维艰
     4 寻路中国:从乡村到工厂的自驾之旅
     5 背包十年:我的职业是旅行
     6 中国历代政治得失
     7 迟到的间隔年
     8 人类简史:从动物到上帝
     9 百年孤独
     10 失控
     11 巨人的陨落:世纪三部曲
     12 从0到1
     13 枪炮、病菌与钢铁:人类社会的命运

like:3
     + 创业维艰 = {'创业维艰'}
hate:7
     + 迟到的间隔年 = {'迟到的间隔年'}
recommend:
    失控 0.22
     0.14
    从0到1 0.03
    枪炮、病菌与钢铁:人类社会的命运 0.03
    背包十年:我的职业是旅行 0.02
    百年孤独 0.02
    人类简史:从动物到上帝 0.01
    寻路中国:从乡村到工厂的自驾之旅 -0.01
    巨人的陨落:世纪三部曲 -0.04
    霍乱时期的爱情 -0.05
```
