Step1: download:  http://an.kaist.ac.kr/~haewoon/release/twitter_social_graph/twitter_rv.tar.gz
This is a twitter graph.
In this case, we use docker to compile it. If you want to run the source code in local, please refer to this 
website https://github.com/GraphChi/graphchi-cpp
Step2
Case1: Getting into docker interactive interface to compile:
Getting into root directory of graphchi(/graphchi-cpp) and then, 
Run: docker run -it xiaogouaiyaotou/realgraphchi:v0
make example_apps/pagerank	 //you can change pagerank to other algorithms
and then run:
bin/example_apps file GRAPH    //GRAPH is your graph location
case2: Compiling it in your shell.
Docker run xiaogouaiyaotou/realgraphchi:v0 make example_apps/pagerank && bin/example_apps/pagerank       //the rule is same as case 1

Here are some results of several algorithms which based on graphchi, all datasets are from the link that I provided at the beginning 
of this document.

