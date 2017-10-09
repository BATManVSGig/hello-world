Lua转换XML文件库： http://download.csdn.net/download/zyj871010/6034733?locationNum=1&fps=1 

# hello-world

you are from really world.I like use Node.js to write some js application to explore
the PC's world.Take a look at the differences.

MXNet设计和实现简介
https://github.com/dmlc/mxnet/issues/797

	   主语言	从语言	     硬件	              分布式	命令式	声明式
Caffe	C++	Python/Matlab	CPU/GPU	            x	    x	    v           不支持分布式训练
Torch	Lua	-	            CPU/GPU/FPGA	      x	    v	    x
Theano	Python	-	      CPU/GPU	            x	    x	    v
TensorFlow	C++	Python	CPU/GPU/Mobile      v	    x	    v           通过gRPC、Protobuf等高性能库实现了神经网络模型的分布式计算
MXNet	C++	Python/R/Julia/Go	CPU/GPU/Mobile	v   	v	    v

pan.baidu.com/s/ldedlxbf
python-3.5.2 +vc-redist.x64

为了介绍TensorFlow的各种用法，我们将使用<deep_recommend_system>这个开源项目，
它实现了TFRecords、QueueRunner、Checkpoint、TensorBoard、Inference、GPU支持、
分布式训练和多层神经网络模型等特性，而且可以轻易拓展实现Wide and deep等模型，
在实际的项目开发中可以直接下载使用。
