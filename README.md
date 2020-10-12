# class1
java  experiment

#阅读内容
用类描述计算机中CPL的速度和硬盘容量

##实验过程
1.首先进行框架设计，在Test主类下有CPU、HardDisk、PC三个分类，主类从分类调取参数并设计和调用显示函数show()达到显示CPU速度以及硬盘容量的目的
2.创建项目Experiment,创建包,在包下进行类的创建和编写
3.创建CPU类、参数speed、方法getSpeed,给speed赋值

##核心方法
1.用Eclipse进行源代码的编译和调试，最后运行出结果
2.用Gitnub来写报告并提交上传
```
public static void main(String args[]){
		  
		  CPU cpu =new CPU();
		  
		  cpu.setSpeed(2200);
		  
		  HardDisk disk=new HardDisk();
		  
		  disk.setAmount(200);
		  
		  PC pc=new PC();
		  pc.setCPU(cpu);
		  pc.setHardDisk(disk);
		pc.show();
		  
		 }
```
##实验结果
CPU速度2200
硬盘容量200

##实验感想
第一次编写Java，学到了用CPU、HardDisk、PC三个分类，学会了传建一些类、参数等并给其赋值。
