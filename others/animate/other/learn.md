## 项目：造物节
### 需求分析：


1. transform 与  perspective

在圆柱绘制完成的时候我们在圆柱的外面，如果需要获得一个好的视角，我们应该在整个圆柱的正中心，所以首先要固定perspective到正中心位置，但是仅仅如此并不能得到好的体验，（这个不好描述，感觉就像是人观察的位置没有变，但是将圆柱在视点的位置抛开，对刨开的部分进行观察），所以还需要通过z轴的位移（与视点相同的，从而得到更好的观察效果）
