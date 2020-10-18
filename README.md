# class1
java  experiment

# 阅读内容
用类描述计算机中CPU的速度和硬盘容量

## 实验过程
1. 在Test主类下有CPU、HardDisk、PC这些分类，在main方法中创建一个CPU对象cpu，然后再创建一个HardDisk对象disk，最后再创建一个PC对象pc
2. 创建项目Experiment,创建包,在包下进行类的创建和编写
3. 创建CPU类、参数speed、方法getSpeed,给speed赋值

## 核心方法
1. 用Eclipse进行源代码的编译和给变量赋值，要符合题目要求，最后通过调试运行得出最终的结果
2. 用把做好的实验通过Gitnub提交并且写设计报告并提交上传

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
CPU cpu;
	  HardDisk disk;
	  void setCPU(CPU cpu){
	   this.cpu=cpu;
	  }
	  void setHardDisk(HardDisk disk){
	   this.disk=disk; 
	  }
	  void show(){
	   System.out.println("CPU速度"+cpu.getSpeed());
	   System.out.println("硬盘容量"+disk.getAmount());
	  }
```

## 实验结果
CPU速度2200
硬盘容量200

## 实验感想
第一次编写Java，学到了用CPU、HardDisk、PC三个分类，学会运用套含关系创建类、参数等并给其赋值。虽然同是编程，但是通过这第一次的编辑发现Java和C语言、python这些编辑手法上不太一样，我觉得目前来说还是有不小难度的，在接下来的学习中我还应该多亲自去动手实践，练习练习，珍惜每一次的实践课。
