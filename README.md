# char-cnn-text-classification-tensorflow
主要用于记录“Character-level Convolutional Networks for Text Classification”论文的模型架构和仿真实现方法。
这是一篇2016年4月份刚发的文章，在此之前，原作者还发表过一篇“Text Understanding from Scratch”的论文，两篇论文基本上是一样的。
可以参见自己的博客http://blog.csdn.net/liuchonge/article/details/70947995

运行命令：
CUDA_VISIBLE_DEVICES="cpu" python training.py

Linux 后台：
CUDA_VISIBLE_DEVICES="cpu" nohup python -u training.py >> output.log 2>&1 &
ps -aux|grep training.py| grep -v grep
netstat -nap|grep 进程号
kill -9  进程号
