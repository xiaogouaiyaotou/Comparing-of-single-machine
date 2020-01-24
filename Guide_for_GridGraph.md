Step 1
---
Before you run this framework, you need to install OpenMP first. <br>
And then, you should run
```
git clone https://github.com/thu-pacman/GridGraph
make
```
Step 2
---
The required data type is edge list, so I don't need to do some data convert.
```
./bin/preprocess -i [input path] -o [output path] -v [vertices] -p [partitions] -t [edge type: 0=unweighted, 1=weighted]
```
