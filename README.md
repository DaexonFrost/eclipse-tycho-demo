

```
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Build Order:
[INFO]
[INFO] max.tycho-rcp-demo.parent                                          [pom]
[INFO] max.tycho-rcp-demo.rcp                                  [eclipse-plugin]
[INFO] max.tycho-rcp-demo.feature                             [eclipse-feature]
[INFO] max.tycho-rcp-demo.aggregator                                      [pom]


[INFO] ---------< max.tychorcpdemo.parent:max.tycho-rcp-demo.parent >----------
[INFO] Building max.tycho-rcp-demo.parent 1.0.0-SNAPSHOT                  [1/4]
[INFO]


[INFO] -----------< max.tychorcpdemo.parent:max.tycho-rcp-demo.rcp >-----------
[INFO] Building max.tycho-rcp-demo.rcp 1.0.0-SNAPSHOT                     [2/4]
[INFO]


[INFO] ---------< max.tychorcpdemo.parent:max.tycho-rcp-demo.feature >---------
[INFO] Building max.tycho-rcp-demo.feature 1.0.0-SNAPSHOT                 [3/4]


[INFO] -------< max.tychorcpdemo.parent:max.tycho-rcp-demo.aggregator >--------
[INFO] Building max.tycho-rcp-demo.aggregator 1.0.0-SNAPSHOT              [4/4]


[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary for max.tycho-rcp-demo.parent 1.0.0-SNAPSHOT:
[INFO]
[INFO] max.tycho-rcp-demo.parent .......................... SUCCESS [  0.062 s]
[INFO] max.tycho-rcp-demo.rcp ............................. SUCCESS [  4.308 s]
[INFO] max.tycho-rcp-demo.feature ......................... SUCCESS [  0.284 s]
[INFO] max.tycho-rcp-demo.aggregator ...................... SUCCESS [  0.002 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  8.317 s
[INFO] Finished at: 2024-05-28T16:39:15+02:00
[INFO] ------------------------------------------------------------------------
```