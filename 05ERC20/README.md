# Erc20智能合约代码
https://github.com/arielwang829/erc20-example/blob/main/lib.rs
- This is the exercise for ERC20 with ink!

# 编译
```cargo +nightly contract build```

# 测试结果 
```cargo +nightly test```
- The test results should be: 
![截屏2021-09-23 下午5.18.28.jpg](https://i.loli.net/2021/09/23/Jd1HzkDvMw2oT69.jpg)

# 运行 Substrate Smart Contracts 节点
```substrate-contracts-node --dev --tmp```

# 部署 Erc20智能合约
- 链接 Canvas UI 到 本地节点

# 操作 Erc20智能合约
## 部署成功
![d1.jpg](https://i.loli.net/2021/09/19/kCxcdQUmo2fV5rl.jpg)

## Instantiated
![d2.jpg](https://i.loli.net/2021/09/19/vBe7jXSMOHElVCi.jpg)
![d4.jpg](https://i.loli.net/2021/09/19/g6DIbNc5wyHPOKJ.jpg)

## Approve（Alice -> Bob）
![d6.jpg](https://i.loli.net/2021/09/19/Fjm9l7G4yBN3k5q.jpg)

## Transfer (Alice -> Ferdie) 
![d7.jpg](https://i.loli.net/2021/09/19/KDOmU657lsie8Nu.jpg)

## Transfer_from (Bob: Alice -> Charlie) 
![d8.jpg](https://i.loli.net/2021/09/19/13hMAtKBYFWHgwC.jpg)
![d9.jpg](https://i.loli.net/2021/09/19/4xSjhMszYEDKmXG.jpg)

## The results of calls
![dx.jpg](https://i.loli.net/2021/09/23/7sUJa5LTuH9pngI.jpg)
