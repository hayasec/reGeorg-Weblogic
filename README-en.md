#### reGeorg Special edition, Apply to old version weblogic.
Normal version in [Neo-reGeorg](https://github.com/L-codes/Neo-reGeorg)或[reGeorg]()(https://github.com/sensepost/reGeorg)

test environment:

docker image：victorrenato/weblogic1036

Normal version error in old version weblogic：

![1](README.assets/1.png)

![4](README.assets/4.png)


Make it to support old version weblogic by editing modifying reGeorgSocksProxy.py

```
python reGeorgSocksProxy_trim.py -p 8888 -l 127.0.0.1 -u http://site.com:7001/tunnelnotrim.jsp
```


![3](README.assets/3.png)

![2](README.assets/2.png)
