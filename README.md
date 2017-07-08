# SANSIGONGXING
Enjoy learning and asking questions; being good at thinking and practising.look for the old so as to learn the new.
 

多媒体技术，登录（一）
<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=gb2312" />
<title>qq快捷登录</title>
</head>

<body>

<table width="442" height="300" frame="hsides">
<tr> <td colspan="2" width="434" height="134" align="center"><a href="1/4.jpg" ><img src="1/1.png"></a></td>
</tr>
<tr><td height="106" colspan="3" ><a href="1/5.jpg">
<img src="1/2.jpg" align="left"></a>
<font color="#0099FF">用户名</font>
<a href="1/3.jpg"><input name="text" type="text"></a><br/>

<font color="#0099FF">密码&nbsp;&nbsp;</font>
<input name="password" type="password"><br/><br/>&nbsp;
<input type="radio" value="是否记住密码？">记住密码
&nbsp;&nbsp;&nbsp;&nbsp;
<input type="radio" value="是否自动登录？">自动登录
</td></tr>
<tr><td height="40" align="center">
<form>
<input Type="submit" value="确定">&nbsp;&nbsp;&nbsp;&nbsp;
<input type="reset" value="重置">
</form></td></tr>
</table>
</body>
</html>
<html>
<head>


<!DOCTYPE html>
<html>
<head>
<title>张三的个人主页</title>
</head>

<body bgcolor="#CCCCCC">

   <p align="center"><font size="7" face="黑体"  color="#FF0000"><u>               <b>                     张三
                                    15级计科1班
                                    欢迎您的到来！
				</b>					</u></font></p>
<p align="center"><font size="+4" face="方正姚体" color="#00FF00">
面朝大海春暖花开<br>
海子当代诗人<br>
从明天起做个幸福的人，<br>
劈柴喂马周游时间，<br>
从明天起关心粮食和蔬菜，<br> 
我有一所房子，<br>
面朝大海春暖花开。<br>
</font></p>
</body>
</html>

<!doctype html>
<html>
<head>

<title>
登录
</title>
<script>
function panduan(){
if(document.getElementById("y").value=="haha"&&document.getElementById("p").value=="123")
{return true;}
else{alert("wrong");return false;}

}
</script>
</head>
<body>
<form action="../多媒体作业/index.html" onSubmit="return panduan()">
 用户 &nbsp; <input type="text" id="y"><br>
 密码 &nbsp; <input type="password" id="p"><br>
 <input type="submit" value="登录"> &nbsp; <input type="reset" value="重置">
</form>
</body>
<style>
form{
border: 2px solid #009999;
margin:200px;
padding:20;
text-align:center;

}
</style>
</html>

<!doctype html>
<html>
<head>

<title>
显示时间
</title>
<script>

 function time(){
document.getElementById("t").value=Date();
}
</script>
</head>
<body>
时间&nbsp;<input type="text"  id="t" size="50"><input type="button" value="刷新" onMouseOver="time()">

</body>
</html>

<!doctype html>
<html>
<head>
<style>
#layout{
 border:4px solid #00FF00;
 marign:50px ;
 background: #FF0000;
}
#d{
text-align:right
}
</style>
<script>
function change(){
if(document.getElementById("consult").innerHTML=="展开")
{document.getElementById("y").innerHTML="我要这天塌，要这地陷，要这轮回破灭，要这世界消散。";
document.getElementById("consult").innerHTML="收缩";}
else
{document.getElementById("y").innerHTML="我要这天塌，要这地陷、、、";
document.getElementById("consult").innerHTML="展开";}
}

</script>
</head>
<title>
 展开
</title>
<body><div id="layout">
<div id="y">我要这天塌，要这地陷、、、</div>
<div id="d"><span id="consult" onClick="change()">展开</span></div>
</div>
</body>
</html>

<!doctype html>
<html>
<head>
<title>电子相册</title>
<script type="text/javascript">
function go(obj)
{
	var s=obj.childNodes[0].src;
    document.getElementById("view").style.display="block";
	document.getElementById("i1").src=s;
	document.body.style.overflow="hidden";
	}
function hide()
{
	var x=document.getElementById("view");
	x.style.display="none";
	document.body.style.overflow="auto";
	}
</script>
</head>
<body style="padding:0px;margin:0px;">
<div style="position:fixed;z-index:100;width:100%;height:100%; background-color:#000000;display:none;text-align:center;" name="view" id="view">
<span style="width:960px;height:100%;text-align:center;" id="show">
<img src="" width="960px" height="100%" id="i1">
</span>
<img src="图/close.png" style="position:absolute;" onClick="hide()">
</div>
<br>
<table width="800" cellspacing="0" cellpadding="0" align="center"  >
<tr align="center">
<td  width="200px" height="200px">
<div onClick="go(this)" style="cursor:hand;"><img  src="图/11.jpg" width="180px" height="180"><br>
  家乡一</div></td>
<td width="200px" height="200px">
<div onClick="go(this)" style="cursor:hand;"><img src="图/9.jpg" width="180" height="180"><br>
   家乡二</div></td>
<td width="200px" height="200px">
<div onClick="go(this)" style="cursor:hand;"><img src="图/12.jpg" width="180" height="180"><br>
   家乡三</div></td>
</tr>
<tr align="center">
<td width="200px" height="200px">
<div onClick="go(this)" style="cursor:hand;"><img src="图/6.jpg" width="180" height="180"><br>
   家乡四</div></td>
<td  width="200px" height="200px">
<div onClick="go(this)" style="cursor:hand;"><img src="图/3.jpg" width="180" height="180"><br>
   家乡五</div></td>
<td width="200px" height="200px">
<div onClick="go(this)" style="cursor:hand;"><img src="图/5.jpg" width="180" height="180"><br> 家乡六</div></td>
</tr>
<tr align="center">
<td width="200px" height="200px">
<div onClick="go(this)" style="cursor:hand;"><img src="图/4.jpg" width="180" height="180"><br> 家乡七</div></td>
<td width="200px" height="200px">
<div onClick="go(this)" style="cursor:hand;"><img src="图/8.jpg" width="180" height="180"><br>
   家乡八</div></td>
<td  width="200px" height="200px">
<div onClick="go(this)" style="cursor:hand;"><img src="图/10.jpg" width="180" height="180"><br> 家乡九</div></td>
</tr>
</table>
</body>
</html>

<html>
<head>
<title>我的家乡</title>
</head>
<body>
<img src="图/18.jpg" border="0" usemap="#Map" />
<a href="3.html" target="_blank"><map name="Map" id="Map">
<area shape="poly" coords="389,254,403,265,411,273,447,281,459,271,445,265,454,244,447,231,427,228">
</map></a>

</body>

</html>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=gb2312" />
<title>无标题文档</title>
</head>

<body><table width="807" height="311"  align="center" cellpadding="0" cellspacing="0">
<tr>

  <td width="375">
<img src="图/zh02_1.jpg" /></td>
  <th width="658"><font size="+4" color="#00FF33">
    <marquee direction="right">个人主页</marquee></font></th>
</tr>
<tr>
  <td ><img src="图/zh02_2.jpg" width="561" height="143" /></td>
</tr>
</table>
<table width="862" align="center" cellpadding="0" cellspacing="0">
<tr>
 <th width="233" rowspan="2" bordercolor="#F0F0F0"><marquee direction="down">
 <p><em><font size="+4"><strong>农蒙古农业大学是自治区重点大学，被誉为塞外花园是高等学府</strong></font></em></p>
 <p>&nbsp;</p>
 <p>&nbsp;</p>
 <p>&nbsp;</p>
 </marquee></th>
 <td width="588"><img src="图/zh02_3(1) - 副本.jpg" width="524" height="147" /></td>
</tr>
<tr>
 <td height="167" align="right"><img src="图/zh02_4.jpg" /></td>
</tr>
</table>
</body>
</html>


<!DOCTYPE html>
<html>
<head>
<title>无标题文档</title>
</head>

<body>
<table align="center" border="4" bordercolor="#0000FF" width="427" height="143">
<tr><td align="center" bgcolor="#00FFFF" rowspan="2">考核成绩</td><td align="center" colspan="2">2002年度</td></tr>
<tr><td align="center">上学期</td><td align="center">下学期</td></tr>
<tr><td align="center" bgcolor="#00FFFF">张三</td><td align="center">优</td><td align="center">及格</td></tr>
<tr><td align="center" bgcolor="#00FFFF">李四</td><td align="center">良</td><td align="center">良</td></tr>
</table>
</body>
</html>


<!DOCTYPE html>
<html>
<head>

<title>无标题文档</title>
</head>

<body>
<table align="center" bgcolor="#CCCCCC" height="270" border="2">
  <tr bgcolor="#00FF66"><th width="343">个人资料</th>
  </tr>
  <tr><td height="199">
  姓名&nbsp;&nbsp;&nbsp;<input type="text"><br>
  性别&nbsp;&nbsp;&nbsp;<input type="radio" value="男">男&nbsp;<input type="radio" value="女">女<br><br>
  出生日期&nbsp;<input type="text"><br><br>
  所学专业&nbsp;<select size="1"><option>数学</option><option>计算机信息工程</option><option>物联网</option></select><br><br>
  所学课程&nbsp;<select size="1"><option>软件工程</option><option>计算机科学</option><option>大学物理</option></select><br><br>
  备注&nbsp;&nbsp;&nbsp;<input type="text"><br><br>
  兴趣&nbsp;&nbsp;&nbsp;<input type="checkbox">篮球&nbsp;<input type="checkbox">游泳&nbsp;<input type="checkbox">帆船</td></tr>
  <tr><td height="25" align="center"><input type="submit" value="提交">&nbsp;&nbsp;&nbsp;<input type="reset" value="置初值"></td></tr>
</table>
</body>
</html>


基础并行程序
/*#include<stdio.h>
#include<mpi.h>
int main(int argc,char *argv[])
{
	int size,rank,i,n,c[10],d[10],a[100],j,x;
	MPI_Init(&argc,&argv);
	MPI_Comm_size(MPI_COMM_WORLD,&size);
	MPI_Comm_rank(MPI_COMM_WORLD,&rank);
n=10;
for(i=0;i<size;i++)
c[i]=n/size;
x=n%size;
for(i=0;i<x;i++)
c[i]++;
for(i=0;i<size;i++)
{
	for(j=0;j<i;j++)
d[i]=d[i]+c[j];
}
for(i=0;i<n;i++)
a[i]=i;
if(rank==0){
for(i=1;i<size;i++)
MPI_Send(a+d[i],c[i],MPI_INT,i,0,MPI_COMM_WORLD);}
else{
MPI_Recv(a,c[rank],MPI_INT,0,0,MPI_COMM_WORLD,MPI_STATUS_IGNORE);
}

	for(i=0;i<c[rank];i++)
printf("%d  ",&a);
		MPI_Finalize();
}*/
/*
#include<stdio.h>
#include<mpi.h>
main(int argv,char* argc[]){
	int size,rank;
	int n,x,a[100],c[10],d[10],i,j;
	MPI_Init(&argv,&argc);
	MPI_Comm_size(MPI_COMM_WORLD,&size);
	MPI_Comm_rank(MPI_COMM_WORLD,&rank);

	printf("进程号:%d\n",rank);
	n=10;
	for(i=0;i<size;i++)c[i]=n/size;
	x=n%size;
	for(i=0;i<x;i++)c[i]++;

	for(i=0;i<size;i++)
	{
	d[i]=0;
	for(j=0;j<i;j++)
	d[i]+=c[j];
	}

		if(rank==0)
		{
			for(i=0;i<n;i++)a[i]=i;
		
			for(i=1;i<size;i++)
			
				MPI_Send(a+d[i],c[i],MPI_INT,i,0,MPI_COMM_WORLD);
				
			}
		
		else
		{
			MPI_Recv(a,c[rank],MPI_INT,0,0,MPI_COMM_WORLD,MPI_STATUS_IGNORE);
		
		}
		
	for(i=0;i<c[rank];i++)*/
	/*
	a[i]=rank;
	if(rank!=0)
	{
	MPI_Send(a,c[rank],MPI_INT,0,0,MPI_COMM_WORLD);
	}
	else
	{
	for(i=1;i<size;i++)
		
	MPI_Recv(a+d[i],c[i],MPI_INT,i,0,MPI_COMM_WORLD,MPI_STATUS_IGNORE);
	for(i=0;i<n;i++)
	printf("%d",a[i]);
	}


	printf("%d",a[i]);
	printf("\n");
	MPI_Finalize();

}  
#include<stdio.h>
#include<mpi.h>
main(int argc,char *argv[])
{int size,rank,a,b,i;
	MPI_Init(&argc,&argv);
	MPI_Comm_size(MPI_COMM_WORLD,&size);
    MPI_Comm_rank(MPI_COMM_WORLD,&rank);
	

	a=rank;
	if(rank!=0)
	{
	MPI_Send(&a,1,MPI_INT,0,0,MPI_COMM_WORLD);
	}

if(rank==0)
	{
	for(i=1;i<size;i++){
	MPI_Recv(&b,1,MPI_INT,i,0,MPI_COMM_WORLD,MPI_STATUS_IGNORE);
	printf("%d\n", b);}
	}
	MPI_Finalize();
}        
#include<stdio.h>
#include<mpi.h>
main(int argc,char* argv[]){
	int size,rank,a,b;
    MPI_Init(&argc,&argv);
		MPI_Comm_size(MPI_COMM_WORLD,&size);
	MPI_Comm_rank(MPI_COMM_WORLD,&rank);
	a=rank;
	MPI_Reduce(&a,&b,1,MPI_INT,MPI_SUM,0,MPI_COMM_WORLD);//0进程接收a的数据进行求和运算再放到b里面
		if(rank==0)
			printf("%d\n",b);
		MPI_Finalize();
}

#include<stdio.h>
#include<mpi.h>
main(int argc,char*argv[]){
	int size,rank,i,a[10],b;
	MPI_Init(&argc,&argv);
	MPI_Comm_size(MPI_COMM_WORLD,&size);
	MPI_Comm_rank(MPI_COMM_WORLD,&rank);
	

	if(rank==0){
		for(i=0;i<size;i++)
		a[i]=i;
		
	}
	MPI_Scatter(&a,1,MPI_INT,&b,1,MPI_INT,0,MPI_COMM_WORLD);
	
	printf("%d:%d\n",rank,b);
	
	MPI_Finalize();


}

#include"stdio.h"
#include"mpi.h"
main(int argc,char*argv[]){
	int size,rank,i,a[10];
	MPI_Init(&argc,&argv);
	MPI_Comm_size(MPI_COMM_WORLD,&size);
	MPI_Comm_rank(MPI_COMM_WORLD,&rank);
	if(rank==0){
		for(i=0;i<size;i++)
			a[i]=i;
	}
	MPI_Bcast(&a,size,MPI_INT,0,MPI_COMM_WORLD);
	printf("%d:",rank);
	for(i=0;i<size;i++)
	printf("%d ",a[i]);
	printf("\n");
	MPI_Finalize();
}

#include"stdio.h"
#include"mpi.h"
main(int argc,char*argv[]){
	int size,rank,a,i,b[10];
	MPI_Init(&argc,&argv);
	MPI_Comm_size(MPI_COMM_WORLD,&size);
	MPI_Comm_rank(MPI_COMM_WORLD,&rank);

		a=rank;
	//	printf("%d:%d\n",rank,a);
	
	MPI_Gather(&a,1,MPI_INT,&b,1,MPI_INT,0,MPI_COMM_WORLD);
	if(rank==0)
	
		for(i=0;i<size;i++)
			printf("%d:%d\n",rank,b[i]);

	MPI_Finalize();

}

#include<stdio.h>
#include<mpi.h>
main(int argc,char*argv[]){
	int size,rank,a,b;
	MPI_Init(&argc,&argv);
	MPI_Comm_size(MPI_COMM_WORLD,&size);
	MPI_Comm_rank(MPI_COMM_WORLD,&rank);
	a=rank;
	MPI_Reduce(&a,&b,1,MPI_INT,MPI_SUM,0,MPI_COMM_WORLD );
	if(rank!=0)
	printf("%d:%d\n",rank,a);
	else
		printf("%d:%d\n",rank,b);
	MPI_Finalize();
}

#include<stdio.h>
#include<mpi.h>
void mp(int*a,int n)
{
	int i,t,j;
	for(i=n;i>=2;i--)
	{
		for(j=0;j<i-1;j++)
			if(a[j]<a[j+1])
			{
				t=a[j];a[j]=a[j+1];a[j+1]=t;
			}
	}
}
	void jo(int*a,int n)
	{
		int i,t,j;
		for(i=0;i<n;i++)
		{
			if(i%2==0)
			{
				for(j=0;j<n-1;j=j+2)
					if(a[j]<a[j+1])
					{
						t=a[j];a[j]=a[j+1];a[j+1]=t;
					}
			}
					else
					{
						for(j=1;j<n-1;j=j+2)
							if(a[j]<a[j+1])
							{
								t=a[j];a[j]=a[j+1];a[j+1]=t;
							}
					}
			
		}
	

	}
main(int argv,char*argc[])
{
	int size,rank;
	int a[100],b[100],i,p,n,local_n,j;
	MPI_Init(&argv,&argc);

	MPI_Comm_size(MPI_COMM_WORLD,&size);
	MPI_Comm_rank(MPI_COMM_WORLD,&rank);
	n=8;
	local_n=n/size;
	if(rank==0){
		for(i=0;i<100;i++)
			a[i]=i;
	}
	MPI_Scatter(a,local_n,MPI_INT,b,local_n,MPI_INT,0,MPI_COMM_WORLD);
	mp(b,local_n);
	for(i=0;i<size;i++)
	{
		if(i%2==0)                  //有偶数个进程时
		{
			if(rank%2==0)
			{
				p=rank+1;
			}
			else
			{
				p=rank-1;
			}
		}
		else                           //有奇数个进程时
		{
			if(rank%2==0)
			{
				p=rank-1;
			}
			else
			{
				p=rank+1;
			}
		}
		if(p==-1||p==size)p=MPI_PROC_NULL;
		if(p!=MPI_PROC_NULL){
			MPI_Send(b,local_n,MPI_INT,p,0,MPI_COMM_WORLD);
			MPI_Recv(b+local_n,local_n,MPI_INT,p,0,MPI_COMM_WORLD,MPI_STATUS_IGNORE);
			mp(b,2*local_n);
			if(rank<p)
			{}
			else
			{
				for(j=0;j<local_n;j++)
					b[j]=b[j+local_n];
			}
		}
	}
/*	for(i=0;i<local_n;i++)printf("%d",b[i]);
	printf("\n");*
	MPI_Gather(b,local_n,MPI_INT,a,local_n,MPI_INT,0,MPI_COMM_WORLD);
	if(rank==0)
		for(i=0;i<n;i++)printf("%d\n",a[i]);
		printf("\n");
		MPI_Finalize();
}

#include<stdio.h>
#include<mpi.h>
main(int argc,char*argv[]){
	int size,rank;
	char b[10];

	int a=1,p;
	MPI_Init(&argc,&argv);
		MPI_Comm_size(MPI_COMM_WORLD,&size);
		MPI_Comm_rank(MPI_COMM_WORLD,&rank);
	if(rank==0){
			p=0;
			MPI_Pack(&a,1,MPI_INT,b,10,&p,MPI_COMM_WORLD);
		}
	MPI_Bcast(&p,1,MPI_INT,0,MPI_COMM_WORLD);
		MPI_Bcast(b,p,MPI_PACKED,0,MPI_COMM_WORLD);//??????????????????????
		
		if(rank!=0){p=0;
			MPI_Unpack(b,10,&p,&a,1,MPI_INT,MPI_COMM_WORLD);
		
		}
		printf("%d:%d\n",rank,a);
		MPI_Finalize();
}

*/





   /*	  if(rank==0){p=0;//指针，置0使其总是指向打包缓冲区尚未使用部分的初始位置
		MPI_Pack(&a,1,MPI_INT,buf,100,&p,MPI_COMM_WORLD);
		MPI_Pack(&b,1,MPI_DOUBLE,buf,100,&p,MPI_COMM_WORLD);
		}
		MPI_Bcast(&p,1,MPI_INT,0,MPI_COMM_WORLD);
		MPI_Bcast(buf,p,MPI_PACKED,0,MPI_COMM_WORLD);	
		if(rank!=0)
		{p=0;
		
			MPI_Unpack(buf,100,&p,&a,1,MPI_INT,MPI_COMM_WORLD);
	    MPI_Unpack(buf,100,&p,&b,1,MPI_DOUBLE,MPI_COMM_WORLD);
		
		}
		printf("%d:a=%d,b=%d\n",rank,a,b);
		MPI_Finalize();
}
*/
#include<stdio.h>
#include<mpi.h>
main(int argc,char*argv[]){
	int size,rank;
	int a[100],b;
	MPI_Init(&argc,&argv);
	MPI_Comm_size(MPI_COMM_WORLD,&size);
	MPI_Comm_rank(MPI_COMM_WORLD,&rank);
	if(rank==0)
	for(i=0;i<100;i++)
		a[i]=i;
	MPI_Type_vector(50,);

}
汇编语言基础
《微机原理》实验报告一二
	实验目的
	熟悉masm开发环境：
	汇编程序的组成，data段、extra段及code段的定义及每段的功能及作用；
	便宜、链接、运行过程；
	Debug调试方式：Ｒ　 Ｔ　 Ｄ指令的使用方法。
	２.编程以掌握以下指令
	ＭＯＶ，ＡＤＤ，ＳＵＢ，ＡＤＣ，ＳＢＢ，ＩＮＣ，ＤＥＣ
	要求把ｍｏｖ指令的非法情况都掌握；
	使用每条指令时要灵活运用不同的寻址方式；
	ＡＤＤ　　ＳＵＢ　　ＡＤＣ　　ＳＢＢ　　ＩＮＣ　　ＤＥＣ　 等指令执行过程结果和状态位的变化。
	3.掌握定义变量的方法和语法；
	在data段或extra段定义DW,DB或DD变量
	4.使用LEA指令获取变量地址；
	5.使用MOV加OFFSET指令实现获取变量地址；
	6.实现无符号双字的加法运算。
	实验环境
	Masm
	实验内容
	DATAS SEGMENT
	 W DW 1111H,2222H,4444H,5555H,6666H
	 Q DW 0
	 D DB 12H,23H,34H
	
	DATAS ENDS
	
	STACKS SEGMENT
	    ;此处输入堆栈段代码
	STACKS ENDS
	
	CODES SEGMENT
	    ASSUME CS:CODES,DS:DATAS,SS:STACKS
	START:
	;此处输入代码段代码
	    MOV AX,DATAS
	    MOV DS,AX
	    MOV AX,4444H
	    ADD AX,W
	    MOV BX,[W+0006H]
	    ADD AX,BX
	    LEA SI,W
	    ADC AX,[SI+0008H]
	    STC
	    INC AX
	    DEC AX
	    MOV [BX],BX
	    SUB AX,[BX]
	    SBB AX,DS:[0008H]
	    
	    MOV CX,OFFSET D
	    LEA DI,D
	    ADC CX,[DI+02H]
	    MOV AX,WORD PTR W
	    MOV DX,WORD PTR [W+CX]
	    ADC AX,DX
	    MOV Q,AX
	
	
	    
	CODES ENDS
	    END START
	实验三
1. 掌握逻辑运算指令：AND   OR    XOR    TEST指令；
（1）将BX中的内容D8，D9两位清零，并将低八位数据设置成89H。
（2）将AX中的内容D5，D4，D1位置1，其余位不变；
（3）将DX中的内容高八位取反，其余位不变。
2. 掌握移位运算指令：SHL    SHR    SAR指令；
注意移位指令对标志位的影响；
3.	将寄存器AL中的内容乘以10。
4.	代码如下：
DATAS SEGMENT
    ;此处输入数据段代码  
DATAS ENDS

STACKS SEGMENT
    ;此处输入堆栈段代码
STACKS ENDS

CODES SEGMENT
	START:
  MOV BX,0111H
  AND BX,0FCFFH;将BX中的内容D8，D9两位清零，并将低八位数据设置成89H。
  MOV AX,1000H
  OR AX,0019H;将AX中的内容D5，D4，D1位置1，其余位不变；
  MOV DX,0011H
  XOR DH,11H;将DX中的内容高八位取反，其余位不变。
  ;第一小题完
  SHL DX,1
  SHR DX,1;无符号位的移动
  SAR DX,1 ;有符号位的移动
  SAL DX,1
  ;第二小题完
    MOV AL,09H
    MOV CL,3;规定必须用CL存储大于3的数
    MOV BL,AL
    SHL AL,CL
    SHL BL,1
    ADD AL,BL ;乘10相当于先左移3位，再加上原数左移1位所得和
    ;第3小题完
    ;实验三完
    
    
CODES ENDS
    END START


	
	
实验四
1.	掌握控制转移类指令：
（1）	判断单个标志位状态：JC/JNC  JZ/JNZ  JP/JNP  JO/JNO
将AX中存放的无符号数除以2，如果是奇数则加1后除以2；
（2）	比较无符号数高低:  JB/JNB   JA/JNA
（3）	比较有符号数大小：JG/JNG   JL/JNL
比较变量a、b的值，找出最大值存入变量c中。
利用控制转移类指令实现1+2+3+…+10，将结果存入result中。
代码：
DATAS SEGMENT
	a DW 0000H
	b DW 0001H
    d DW 0000H
    result DW 0000H
    ;此处输入数据段代码  
DATAS ENDS

STACKS SEGMENT
    ;此处输入堆栈段代码
STACKS ENDS
CODES SEGMENT
    ASSUME CS:CODES,DS:DATAS,SS:STACKS
START:
MOV AX,DATAS
MOV DS,AX
  
    MOV AX,1001H
    SHR AX,1 
    JP Q;JP（奇偶标志）PF为1转移
    Q:INC AX;AX+1
;第(1)小题完
     MOV BX,0101H
     MOV CX,0011H
     CMP BX,CX
     JNB W;大于就跳
     MOV DX,CX
    W:MOV DX,BX
    ;第（2）小问完
   MOV BX,a
     MOV CX,b
     MOV DX,d
     CMP BX,CX
     JG E;更大就跳
     MOV DX,CX
    E:MOV DX,BX
  MOV CX,a
    MOV BX,b
AD: ADD CX,BX
     INC BX
    ;此处输入代码段代码
    CMP BX,10
    JB AD
    MOV result,CX


    ;完
  
    ;此处输入代码段代码
   
CODES ENDS
    END START




