

```
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Build Order:
[INFO]
[INFO] max.tycho-rcp-demo.parent                                          [pom]
[INFO] max.tycho-rcp-demo.rcp                                  [eclipse-plugin]
[INFO] max.tycho-rcp-demo.aggregator                                      [pom]
[INFO]
[INFO] ---------< max.tychorcpdemo.parent:max.tycho-rcp-demo.parent >----------
[INFO] Building max.tycho-rcp-demo.parent 1.0.0-SNAPSHOT                  [1/3]
[INFO]   from pom.xml
[INFO] --------------------------------[ pom ]---------------------------------
[INFO]
[INFO] --- clean:3.2.0:clean (default-clean) @ max.tycho-rcp-demo.parent ---
[INFO]
[INFO] -----------< max.tychorcpdemo.parent:max.tycho-rcp-demo.rcp >-----------
[INFO] Building max.tycho-rcp-demo.rcp 1.0.0-SNAPSHOT                     [2/3]
...
[INFO] -------< max.tychorcpdemo.parent:max.tycho-rcp-demo.aggregator >--------
[INFO] Building max.tycho-rcp-demo.aggregator 1.0.0-SNAPSHOT              [3/3]
[INFO] --------------------------------[ pom ]---------------------------------
[INFO]
[INFO] --- clean:3.2.0:clean (default-clean) @ max.tycho-rcp-demo.aggregator ---
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary for max.tycho-rcp-demo.parent 1.0.0-SNAPSHOT:
[INFO]
[INFO] max.tycho-rcp-demo.parent .......................... SUCCESS [  0.066 s]
[INFO] max.tycho-rcp-demo.rcp ............................. SUCCESS [  4.665 s]
[INFO] max.tycho-rcp-demo.aggregator ...................... SUCCESS [  0.002 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  8.418 s
[INFO] Finished at: 2024-05-28T16:08:57+02:00
[INFO] ------------------------------------------------------------------------
```