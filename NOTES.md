> wget https://mirrors.bfsu.edu.cn/apache/zookeeper/zookeeper-3.7.0/apache-zookeeper-3.7.0-bin.tar.gz
> tar zxvf zookeeper-3.7.0/apache-zookeeper-3.7.0-bin.tar.gz
> cd  mv zookeeper-3.7.0/apache-zookeeper-3.7.0-bin
> mv conf/zoo_sample.cfg conf/zoo.cfg
> ./bin/zkServer.sh  start
> ./bin/zkCli.sh
