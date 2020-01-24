Step 1
---
First you need to install boost in your machine. You can following this guide to install it.
https://www.osetc.com/en/how-to-install-boost-on-ubuntu-16-04-18-04-linux.html https://www.osetc.com/en/how-to-install-boost-on-ubuntu-16-04-18-04-linux.html
After you finished the install, get my revised version, the original version has a lot of trouble in my machine so I edited it somewhere.
```
git clone git@github.com:xiaogouaiyaotou/x-stream-edition.git
```
Step2
---

The author of the X-Stream provided two method to run the framwork, one is use a generator to generator a dataset.
```
rmat --name test --scale 20 --edges 16777216
```
To ensure the authenticity of the data, all the datasets are real data from various social media. All the data type I get is edge list, <br>
and the required data type is binary edge list. So I wrote some convert file to convert the data and you can find it in my other repo.<br>
After you have the right data type, you can run it use
```
benchmark_driver -g test -b pagerank --pagerank::niters 10 -a -p 16 --physical_memory 268435456
```

