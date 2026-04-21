# GitHub README（最小 Origin 版）

# Generic π (ジェネリック円周率)

π_gen(n) = n * sin(π/n)

- n: 帯の方向数
- π_gen(n): n方向帯で生成される円の円周率

lim n→∞ π_gen(n) = π

## Origin
Qiita Origin Article:
https://qiita.com/ToyohroArimoto/items/020fe20e228c93dc4c37

Initial Commit Hash:
e80b1938c20f1af19cb8ee4dbeb7171f45a3b836

---
## 帯OSの閉じ方（Closure Condition）

帯OS幾何学では、方向数 n と方向角 θ が
世界を一周して閉じる条件は次で与えられる。

nθ = 2π

この式は円を前提とせず、方向の総和が世界を閉じる
OSレベルの条件である。

この閉じ方から、Generic π が自然に導かれる。
