rmtorecycle
====
## Install
```
wget https://github.com/Fangyh09/rm/blob/master/rmtorecycle.sh
```

#### Author:ymc023  Email:ymc023@163.com
____

#### 刚刚把备份的脚本和恢复脚本整理完，然后就是把多余的数据rm掉，然后，我就用了rm -rf ......<br>
#### 然后，我就发现，我刚写好的东西也一起rm了，心里那个悔呀！哎...... <br>

#### 所以，就有了用mv替换rm的脚本，使用方法如下: <br>
　
##### 运行脚本将下面的内容追加到~/.bashrc <br>
##### 运行完脚本请source ~/.bashrc <br>
##### 脚本会在当前用户家目录下创建.recycle <br>
##### 重名文件会提示覆盖，但会备份在.recycle下，备份格式:*.~*~ <br>

##### 使用rm删除文件时,会使用mv移动至~/.recycle  <br>
##### 使用rmls查看回收筒内的文件  <br>
##### 使用undorm <*> 恢复被删除的文件到当前路径下 <br>
##### 使用cltrash 清除~/.recycle下的全部文件 <br>
