### 2147.Number-of-Ways-to-Divide-a-Long-Corridor

本题的思想非常简单，就是将每两个沙发作为一组，然后查看每组之间有几个植物。这些植物之间、植物与两侧的沙发之间都可以插板。然后用乘法原理计算总的策略数目。

本题如果在原数组上操作，会显得有些繁琐。直接将沙发的index拿出来放在一个新数组里，这样每相邻两个元素一组，每组之间的间隔就一目了然。