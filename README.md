1.1版本是Qt翻金币代码以及打包出来的应用程序---无需下载qt也能运行             
各位自己打包的时候记得使用qt的命令终端，并且将缺少的动态链接库(.dll)从qt中搜索出来并且复制到打包的目录文件夹中                     
2.0版本是做了从第一关开始一关一关解锁的功能，大家可以克隆回去用qt运行，因为我打包的时候怎么都运行不了，搞了大半天，不知道是不是1.1版本的程序跟这个冲突了       
（我记得推送到github的时候没有没有把relese放进去，因为运行不了嘛，但从我这看这个版本里面确实有一个程序包，反正我运行不了！）                        
突然发现！！！！！！！大家下载后的CoinFlip2 在运行前一定要把名字改回CoinFlip(因为里面有一个文件打开路径)，如果还是有问题就用记事本打开CoinFlip.pro.user,使用查找功能把CoinFlip2都替换成CoinFlip
