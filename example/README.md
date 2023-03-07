
# Correct Results
```
Decision tree:
0:[f0<0.5],cover=5
        1:leaf=-1,cover=2
        2:[f1<0.5],cover=3
                3:leaf=-1,cover=1
                4:[f2<0.5],cover=2
                        5:leaf=1,cover=1
                        6:leaf=0.5,cover=1
Extracted paths:
path_idx:0, leaf value:-1
 (feature:-1, pz:1, [-inf<=x<inf])
 (feature:0, pz:0.4, [-inf<=x<0.5])
path_idx:1, leaf value:-1
 (feature:-1, pz:1, [-inf<=x<inf])
 (feature:0, pz:0.6, [0.5<=x<inf])
 (feature:1, pz:0.333333, [-inf<=x<0.5])
path_idx:2, leaf value:1
 (feature:-1, pz:1, [-inf<=x<inf])
 (feature:0, pz:0.6, [0.5<=x<inf])
 (feature:1, pz:0.666667, [0.5<=x<inf])
 (feature:2, pz:0.5, [-inf<=x<0.5])
path_idx:3, leaf value:0.5
 (feature:-1, pz:1, [-inf<=x<inf])
 (feature:0, pz:0.6, [0.5<=x<inf])
 (feature:1, pz:0.666667, [0.5<=x<inf])
 (feature:2, pz:0.5, [0.5<=x<inf])

Row 0 contributions:
f0:0.627778 f1:0.502778 f2:0.169444 bias:-0.3
Row 1 contributions:
f0:0.538889 f1:0.430556 f2:-0.169444 bias:-0.3
```
