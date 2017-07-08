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


数据结构基础
1. 1.对于下列带表头结点的单链表,写出指向
   数据域为X的结点的指针移动语句,要求头指针保持不变.
template <class T1>int List<T1>::Delete(int x)
{	 
	ListNode<T1>  *q,*p;
	if(LA->date==x)
	{	LA=LA->next;}
	else{
	q=LA;
   while(q->next->date!=x)
   {q=q->next;}
	   p=q->next;
   q->next=p->next;
   delete p;}
   return 1;
}

2. 写出在无头结点的单链表的第一个结点之前插入S结点的语句.
template<class q>int List<q>::Ins(q a)
{
ListNode<q> *s;
s=new ListNode<q>;
s->date=a;
s->next=LB;
LB=s;
return 1;
}
3.假设有一个单链表的长度大于1,且表中无头结点，头指针为L.已知S(S≠L)为指向链表中某结点的指针,试编写算法在链表中删除指针S所指结点的前驱结点.

#include<iostream.h>
#include<stdlib.h>
template<class q>class List;
template<class q>class ListNode
{
	friend class List<q>;
	private:
		q date;
		ListNode<q> *next;
};
template<class q>class List
{
	public:
		List(){L=NULL;}
		int cre(int n);
		int Ins(int i, q a);
		int Delete(int i,q &a);
		void prnl();
	private:
		ListNode<q>*L;
};
template<class q>int List<q>::cre(int n)
{
	ListNode<q> *p ,*r;
int i;
p=new ListNode<q>;
L=p;r=p;p->next=NULL;
cin>>p->date;
for(i=n-1;i>0;--i)
{p=new ListNode<q>;
cin>>p->date;
p->next=NULL;
r->next=p;
r=p;}
return 1;
}
template<class q>int List<q>::Delete(int i, q &a)
{
	ListNode<q> *b,*S;
int j;
if(i==1){ 
	L=L->next;}
else
{b=L;j=1;
while(b!=NULL&&j<i-2)
{b=b->next;
j++;}
if(b==NULL||j>i-2)
return 0;
S=b->next;
b->next=S->next;
a=S->date;
}
delete S;
return 1;
}

template<class q>void List<q>::prnl()
{
ListNode<q> *w;
w=L;
while(w!=NULL)
{cout<<w->date<<endl;
w=w->next;}
}
void main()
{List<int> k;
int n,j1,x1;
cout<<"请输入结点个数"; 
 cin>>n;
 k.cre(n);
k.prnl();
cout<<"请输入删除位置";
cin>>j1;
k.Delete(j1,x1);
k.prnl();
cout<<"输出被删除元素："<<endl;
 cout<<x1<<endl;
}
 

1.对于下列带表头结点的单链表,写出指向
   数据域为Z的结点的指针移动语句,并且删除该结点，要求头指针保持不变。（假设链表非空，且只有一个结点数据域为Z）
template <class T1>int List<T1>::Delete(int z)
{	 
	ListNode<T1>  *q,*p;
	if(LA->date==z)
	{	LA=LA->next;}
	else{
	q=LA;
   while(q->next->date!=z)
   {q=q->next;}
	   p=q->next;
   q->next=p->next;
   delete p;}
   return 1;
}
2.写出在无头结点的单链表的第一个结点之前插入P结点的语句.
template<class q>int List<q>::Ins(q a)
{
ListNode<q> *p;
p=new ListNode<q>;
p->date=a;
p->next=LB;
LB=p;
return 1;
}
3.假设有一个单链表的长度大于1,且表中无头结点，头指针为LA.已知R(R≠LA)为指向链表中某结点的指针,试编写算法在链表中删除指针R所指结点。
#include<iostream.h>
#include<stdlib.h>
template<class q>class List;
template<class q>class ListNode
{
	friend class List<q>;
	private:
		q date;
		ListNode<q> *next;
};
template<class q>class List
{
	public:
		List(){LA=NULL;}
		int cre(int n);
		int Ins(int i, q a);
		int Delete(int i,q &a);
		void prnl();
	private:
		ListNode<q>*LA;
};
template<class q>int List<q>::cre(int n)
{
	ListNode<q> *p ,*r;
int i;
p=new ListNode<q>;
LA=p;r=p;p->next=NULL;
cin>>p->date;
for(i=n-1;i>0;--i)
{p=new ListNode<q>;
cin>>p->date;
p->next=NULL;
r->next=p;
r=p;}
return 1;
}
template<class q>int List<q>::Delete(int i, q &a)
{
	ListNode<q> *b,*R;
int j;
if(i==1){ 
	LA=LA->next;}
else
{b=LA;j=1;
while(b!=NULL&&j<i-1)
{b=b->next;
j++;}
if(b==NULL||j>i-1)
return 0;
R=b->next;
b->next=R->next;
a=R->date;
}
delete R;
return 1;
}

template<class q>void List<q>::prnl()
{
ListNode<q> *w;
w=LA;
while(w!=NULL)
{cout<<w->date<<endl;
w=w->next;}
}
void main()
{List<int> k;
int n,j1,x1;
cout<<"请输入结点个数";
 cin>>n;
 k.cre(n);
k.prnl();
cout<<"请输入删除位置";
cin>>j1;
k.Delete(j1,x1);
k.prnl();
cout<<"输出被删除元素："<<endl;
 cout<<x1<<endl;
}

4.假设有一个单链表非空,且带头结点，头指针为L，试编写算法计算线性表的长度并输出。
template<class q>void List<q>::length()
{int j=0;
ListNode<q> *w;
w=L;
while(w!=NULL)
{j++;
w=w->next;}
cout<<j<<endl;
}



1
#include<iostream.h>
#include<stdlib.h>
template<class q>class List;
template<class q>class ListNode
{
	friend class List<q>;
	private:
		q date;
		ListNode<q> *next;
};
template<class q>class List
{
	public:
		List(){
			L=new ListNode<q>;
			L->next=NULL;}
		int cre(int n);
		void length();
	private:
		ListNode<q>*L;
};
template<class q>int List<q>::cre(int n)
{
	ListNode<q> *p ,*r;
int i;
p=new ListNode<q>;
L=p;r=p;p->next=NULL;
cin>>p->date;
for(i=n-1;i>0;--i)
{p=new ListNode<q>;
cin>>p->date;
p->next=NULL;
r->next=p;
r=p;}
return 1;
}
template<class q>void List<q>::length()
{int j=0;
ListNode<q> *w;
w=L;
while(w!=NULL)
{j++;
w=w->next;}
cout<<j<<endl;
}
void main()
{List<int> k;
int n,j1,x1,j2,x2;
cout<<"请输入结点个数";
 cin>>n;
 k.cre(n);
cout<<"请输出结点长度";
k.length();
}

2. 编写在无头结点的动态单链表上实现线性表操作INSERT(L,i,b)和DELETE(L,i)的算法，并和在带头结点的动态单链表上实现相同操作的算法进行比较．
#include<iostream.h>
#include<stdlib.h>
template<class q>class List;
template<class q>class ListNode
{
	friend class List<q>;
	private:
		q date;
		ListNode<q> *next;
};
template<class q>class List
{
	public:
		List(){L=NULL;}
		int cre(int n);
		int INSERT(int i, q a);
		int DELETE(int i,q &a);
		void prnl();
	private:
		ListNode<q>*L;
};
template<class q>int List<q>::cre(int n)
{
	ListNode<q> *p ,*r;
int i;
p=new ListNode<q>;
L=p;r=p;p->next=NULL;
cin>>p->date;
for(i=n-1;i>0;--i)
{p=new ListNode<q>;
cin>>p->date;
p->next=NULL;
r->next=p;
r=p;}
return 1;
}
template<class q>int List<q>::INSERT(int i,q a)
{	int j;
ListNode<q> *y,*z;
if(i==1){
z=new ListNode<q>;
z->date=a;
z->next=L;
z=L;}
else{
	y=L;j=1;
while(y!=NULL&&j<i-1)
{y=y->next;
j++;}
if(y==NULL||j>i-1)
return 0;
z=new ListNode<q>;
if(z==NULL) exit(0);
z->date=a;
z->next=y->next;
y->next=z;}
return 1;
}

template<class q>int List<q>::DELETE(int i, q &a)
{
	ListNode<q> *b,*c;
int j;
if(i==1){ 
	L=L->next;}
else
{b=L;j=1;
while(b!=NULL&&j<i-1)
{b=b->next;
j++;}
if(b==NULL||j>i-1)
return 0;
c=b->next;
b->next=c->next;
a=c->date;
}
delete c;
return 1;
}

template<class q>void List<q>::prnl()
{
ListNode<q> *w;
w=L;
while(w!=NULL)
{cout<<w->date<<endl;
w=w->next;}
cout<<endl; 
}
void main()
{List<int> k;
int n,j1,x1,j2,x2;
cout<<"请输入结点个数与插入位置、插入元素";
 cin>>n>>j1>>x1;
 k.cre(n);
k.INSERT(j1,x1);
k.prnl();
cout<<"请输入删除位置";
cin>>j2;
k.DELETE(j2,x2);
k.prnl();
cout<<"输出被删除元素："<<endl;
 cout<<x2<<endl;
}
实验1      利用顺序存储结构存储线性表插入操作的实现。要求数据元素为学号、姓名、成绩1、成绩2四个域。
实验一
#include <iostream.h>
#include <stdlib.h>
#include <string.h>
typedef char ZF[15];
template <class A1,class A2,class A3> class SeqList;	           
 template <class A1,class A2,class A3> class SListNumde {	       	
 friend class SeqList<A1,A2,A3>;	      
 private:
     A1 num;
     A2 score1;
     A3 score2;	
	 ZF name;
 };
template <class A1,class A2,class A3> class SeqList{
      private:
          SListNumde<A1,A2,A3>  *elem;    
	      int Max;	    	
	      int len; 	
	  public:
		  int Ins(A1 x1,ZF x2,A2 x3,A3 x4, int i);
		  void cre(int n);
	 	  int  Remove(A1 &x1,ZF &x2,A2 &x3,A3 &x4,int i );
};		      
template <class A1,class A2,class A3> void SeqList<A1,A2,A3>::cre(int n)
{
	 int i,j;
    len=0;Max=n;elem=new  SListNumde<A1,A2,A3>[n]; 
	cout<<"输入元素个数";
	cin>>j;
    for(i=0;i<j;i++)
   		cin>>elem[i].num>>elem[i].name>>elem[i].score1>>elem[i].score2;
	len=j;
	for(i=0;i<len;i++)
 cout<<elem[i].num <<" "<<elem[i].name<<" "<<elem[i].score1<<" "<<elem[i].score2<<endl;
	cout<<endl;
}
template <class A1,class A2,class A3> int SeqList<A1,A2,A3>::Ins(A1 x1,ZF x2,A2 x3,A3 x4, int i)
 {
    int j;
	if (i<1||i>len+1)  return 0;      
   					       
       for(j=len;j>=i;j--)
          elem[j]=elem[j-1];		
     elem[i-1].num=x1; strcpy(elem[i-1].name,x2);elem[i-1].score1=x3 ;elem[i-1].score1=x4; 
		  len++;	
		  cout<<"输出插入后的线性表"<<endl;
		  for(int k=0;k<len;k++)
cout<<elem[k].num<<" "<<elem[k].name <<" "<<elem[k].score1<<" "<<elem[k].score2 <<endl;
		  cout<<endl;
          return 1;              
     }
void main()
{
	SeqList <int,int,int> L;
	int n,i;
	int c1,c3,c4;
	ZF c2;
	cout<<"输入n的值";
	cin>>n;
	L.cre(n);
	cout<<"输入i,c1,c2,c3的值";
	cin>>i>>c1>>c2>>c3>>c4;
	L.Ins(c1,c2,c3,c4,i);
   }
实验2      利用顺序存储结构存储线性表删除操作的实现。要求数据元素为学号、姓名、成绩1、成绩2四个域。
实验二
#include <iostream.h>
#include <stdlib.h>
#include <string.h>
typedef char ZF[15];
template <class A1,class A2,class A3> class SeqList;	           
 template <class A1,class A2,class A3> class SListNumde {	       	
 friend class SeqList<A1,A2,A3>;	      
 private:
     A1 num;
     A2 score1;
     A3 score2;	
	 ZF name;
 };
template <class A1,class A2,class A3> class SeqList{
      private:
          SListNumde<A1,A2,A3>  *elem;    
	      int Max;	    	
	      int len; 	
	  public:
		  int Ins(A1 x1,ZF x2,A2 x3,A3 x4, int i);
		  void cre(int n);
	 	  int  Remove(A1 &x1,ZF &x2,A2 &x3,A3 &x4,int i );
};		      
template <class A1,class A2,class A3> void SeqList<A1,A2,A3>::cre(int n)
{
	 int i,j;
    len=0;Max=n;elem=new  SListNumde<A1,A2,A3>[n]; 
	cout<<"输入元素个数";
	cin>>j;
    for(i=0;i<j;i++)
   		cin>>elem[i].num>>elem[i].name>>elem[i].score1>>elem[i].score2;
	len=j;
	for(i=0;i<len;i++)
 cout<<elem[i].num <<" "<<elem[i].name<<" "<<elem[i].score1<<" "<<elem[i].score2<<endl;
	cout<<endl;
}
template <class A1,class A2,class A3> int SeqList<A1,A2,A3>::Ins(A1 x1,ZF x2,A2 x3,A3 x4, int i)
 {
    int j;
	if (i<1||i>len+1)  return 0;      
   					       
       for(j=len;j>=i;j--)
          elem[j]=elem[j-1];		
     elem[i-1].num=x1; strcpy(elem[i-1].name,x2);elem[i-1].score1=x3 ;elem[i-1].score1=x4; 
		  len++;	
		  cout<<"输出插入后的线性表"<<endl;
		  for(int k=0;k<len;k++)
cout<<elem[k].num<<" "<<elem[k].name <<" "<<elem[k].score1<<" "<<elem[k].score2 <<endl;
		  cout<<endl;
          return 1;              
     }
template <class A1,class A2,class A3> int SeqList<A1,A2,A3>::Remove(A1 &x1,ZF &x2,A2 &x3,A3 &x4,int i)
 {	
      if (i<1||i>len)	  return 0;      
	x1=elem[i-1].num;strcpy(x2,elem[i-1].name);x3=elem[i-1].score1; x4=elem[i-1].score2;			
	  for(int j=i;j<len;j++) 
              elem[j-1]=elem[j];
	    len--;	
		cout<<"输出删除后的线性表"<<endl;
      for(int k=0;k<len;k++)
 cout<<elem[k].num<<" "<<elem[k].name <<" "<<elem[k].score1<<" "<<elem[k].score2<<endl;
      cout<<endl;
         return 1;	     
     }	

void main()
{
	SeqList <int,int,int> L;
	int n,i,i1;
	int c1,c3,c4,d1,d3,d4;
	ZF c2,d2;
	cout<<"输入n的值";
	cin>>n;
	L.cre(n);
	cout<<"输入i,c1,c2,c3的值";
	cin>>i>>c1>>c2>>c3>>c4;
	L.Ins(c1,c2,c3,c4,i);
	cout<<"输入i1的值";
	cin>>i1;
	L.Remove(d1,d2,d3,d4,i1);
    cout<<"被删除的元素为：";
	cout<<d1<<" "<<d2<<" "<<d3<<" "<<d4;
   }
实验3      利用链式存储结构存储线性表插入操作的实现。要求数据元素为学号、姓名、成绩1、成绩2四个域。
实验三
#include <iostream.h>
#include <stdlib.h>
#include <string.h>
typedef char ZF[20];
template <class A1,class A2,class A3> class List;	            //复合类定义
 template <class A1,class A2,class A3> class ListNode {	        //链表结点类	
 friend class List<A1,A2,A3>;	        //链表类为其友元类
 private:
     A1 num;
     A2 sc1;
	 A3 sc2;
	 ZF name;//结点数据, 整型	
     ListNode<A1,A2,A3> *next;   
  		
 };
 template <class A1,class A2,class A3> class List{	                  //链表类		
 public:
      //链表公共操作
	 List(){L=NULL;}
	 int cre(int n);
	 int Ins(int i,A1 e1,ZF e4,A2 e2,A3 e3);
	 int Delete(int i,A1 &e1,ZF &e4,A2 &e2,A3 &e3);
	 void prnl();
 private:
     ListNode<A1,A2,A3> *L;    //表头和表尾指针
 };
 template <class A1,class A2,class A3> int List<A1,A2,A3>::cre(int n)
 { 
  ListNode<A1,A2,A3>  *p,*r;
   int i;
   p=new ListNode<A1,A2,A3>;
   L=p;r=p;p->next=NULL;
   for(i=n;i>0;--i){ 
	 p=new ListNode<A1,A2,A3>;
	 cin>>p->num>>p->name>>p->sc1>>p->sc2;
     p->next=NULL;r->next=p;
	 r=p;
	  }
   return 1;
 }
 
template <class A1,class A2,class A3> void List<A1,A2,A3>::prnl( )
{	 
	ListNode<A1,A2,A3>  *q;
	q=L->next;
   while(q!=NULL){
	cout<<q->num<<" "<<q->name<<" "<<q->sc1<<" "<<q->sc2<<endl;
    q=q->next;}
   cout<<endl;
}
 template <class A1,class A2,class A3>int List<A1,A2,A3>::Ins(int i, A1 e1,ZF e4,A2 e2,A3 e3)
 {int j;
  ListNode<A1,A2,A3>  *y,*z;
  
	  y=L;j=0;
      while(y!=NULL && j<i-1){
	    y=y->next;
        ++j;
	  }
      if(y==NULL || j>i-1) return 0;
      z=new ListNode<A1,A2,A3>;
      if(z==NULL) exit(0);
      z->num=e1;z->sc1=e2;z->sc2=e3; strcpy(z->name,e4);
      z->next=y->next;
      y->next=z;
      return 1;
}
void main()
{
 List <int,int,int> K;
  
 int n,j1;
 int x1,y1,z1;
 ZF h1;
 cout<<"请输入学生（结点）人数与各学生情况（元素）"<<endl;
 cin>>n;
 K.cre(n);
 K.prnl();
 cout<<"请输入插入位置、插入元素"<<endl;
 cin>>j1>>x1>>h1>>y1>>z1;
 K.Ins(j1,x1,h1,y1,z1);
 K.prnl();
}
实验4      利用链式存储结构存储线性表删除操作的实现。要求数据元素为学号、姓名、成绩1、成绩2四个域。
实验四

#include <iostream.h>
#include <stdlib.h>
#include <string.h>
typedef char ZF[20];
template <class A1,class A2,class A3> class List;	            //复合类定义
 template <class A1,class A2,class A3> class ListNode {	        //链表结点类	
 friend class List<A1,A2,A3>;	        //链表类为其友元类
 private:
     A1 num;
     A2 sc1;
	 A3 sc2;
	 ZF name;//结点数据, 整型	
     ListNode<A1,A2,A3> *next;   
  		
 };
 template <class A1,class A2,class A3> class List{	                  //链表类		
 public:
      //链表公共操作
	 List(){L=NULL;}
	 int cre(int n);
	 int Ins(int i,A1 e1,ZF e4,A2 e2,A3 e3);
	 int Delete(int i,A1 &e1,ZF &e4,A2 &e2,A3 &e3);
	 void prnl();
 private:
     ListNode<A1,A2,A3> *L;    //表头和表尾指针
 };
 template <class A1,class A2,class A3> int List<A1,A2,A3>::cre(int n)
 { 
  ListNode<A1,A2,A3>  *p,*r;
   int i;
   p=new ListNode<A1,A2,A3>;
   L=p;r=p;p->next=NULL;
   for(i=n;i>0;--i){ 
	 p=new ListNode<A1,A2,A3>;
	 cin>>p->num>>p->name>>p->sc1>>p->sc2;
     p->next=NULL;r->next=p;
	 r=p;
	  }
   return 1;
 }
 
template <class A1,class A2,class A3> void List<A1,A2,A3>::prnl( )
{	 
	ListNode<A1,A2,A3>  *q;
	q=L->next;
   while(q!=NULL){
	cout<<q->num<<" "<<q->name<<" "<<q->sc1<<" "<<q->sc2<<endl;
    q=q->next;}
   cout<<endl;
}
 template <class A1,class A2,class A3>int List<A1,A2,A3>::Ins(int i, A1 e1,ZF e4,A2 e2,A3 e3)
 {int j;
  ListNode<A1,A2,A3>  *y,*z;
  
	  y=L;j=0;
      while(y!=NULL && j<i-1){
	    y=y->next;
        ++j;
	  }
      if(y==NULL || j>i-1) return 0;
      z=new ListNode<A1,A2,A3>;
      if(z==NULL) exit(0);
      z->num=e1;z->sc1=e2;z->sc2=e3; strcpy(z->name,e4);
      z->next=y->next;
      y->next=z;
      return 1;
}
  template <class A1,class A2,class A3> int List<A1,A2,A3>::Delete(int i,A1 &e1,ZF &e4,A2 &e2,A3 &e3)
  {
   ListNode<A1,A2,A3>  *p,*q;
   int j;
   
	     p=L;  j=0;
	     while (p->next && j<i-1)
		 {p=p->next;  ++j;}
		 if (!(p->next) || j>i-1) return 0;
		 q=p->next;  p->next=q->next;
         e1=q->num; e2=q->sc1;e3=q->sc2; strcpy(e4,q->name);
		 delete  q;
		 return 1;
  }

void main()
{
 List <int,int,int> K;
  
 int n,j1,j2;
 int x1,y1,x2,y2,z1,z2;
 ZF h1,h2;
 cout<<"请输入学生（结点）人数与各学生情况（元素）"<<endl;
 cin>>n;
 K.cre(n);
 K.prnl();
 cout<<"请输入插入位置、插入元素"<<endl;
 cin>>j1>>x1>>h1>>y1>>z1;
 K.Ins(j1,x1,h1,y1,z1);
 K.prnl();
 cout<<"请输入删除位置"<<endl;
 cin>>j2;
 K.Delete(j2,x2,h2,y2,z2);
 K.prnl();
 cout<<"被删除元素的学号，姓名，成绩1，成绩2为："<<endl;
 cout<<x2<<""<<h2<<" "<<y2<<" "<<z2<<endl;
}
实验5      利用顺序存储结构存储栈时栈抽象数据类型的实现。要求数据元素为学号、姓名、年龄、总分四个域。
实验五
#include<iostream.h>
#include<stdlib.h>
#include<string.h>
const int length=10;
typedef char ZF[20];
template <class A1,class A2,class A3>class stack;
template<class A1,class A2,class A3>class stacknode{
friend class stack<A1,A2,A3>;
private:
	ZF name;
	A1 num;
	A2 score1;
	A3 score2;
	stacknode<A1,A2,A3> *point;
};
template <class A1,class A2,class A3>class stack{
public:
	stack();
	void create(int n);
	void print();
	int push(A1 e1,ZF e,A2 e2,A3 e3);
private:
	stacknode<A1,A2,A3> *top,*base;
	int stacksize;
};
template <class A1,class A2,class A3>
stack<A1,A2,A3>::stack(){
	base=new stacknode<A1,A2,A3>[length];
	top=base;
	stacksize=length;
}
 template <class A1,class A2,class A3>
	 void stack<A1,A2,A3>::create(int n){
	 for(int i=1;i<=n;++i){
	 cin>>(*top).num>>(*top).name>>(*top).score1>>(*top).score2;
	 ++top;
	 }
 }
 template <class A1,class A2,class A3>
	 void stack<A1,A2,A3>::print(){
 stacknode<A1,A2,A3> *r;
 for(r=top-1;r>=base;r--){
 cout<<(*r).num<<" "<<(*r).name<<" "<<(*r).score1<<" "<<(*r).score2<<endl;
 }}
template <class A1,class A2,class A3>
int stack<A1,A2,A3>::push(A1 e1,ZF e,A2 e2,A3 e3){
(*(top)).num=e1;
strcpy((*(top)).name,e);
(*(top)).score1=e2;
(*(top)).score2=e3;
++top;
return 1;
}

 void main(){
 stack<int, int,int>M;
 int n,b,s1,s2;
 ZF e;
 cout<<"请输入学生人数"<<endl;
cin>>n;
cout<<"请输入学号，姓名，成绩1，成绩2"<<endl;
 M.create(b);
 cout<<"输出顺序栈表为"<<endl;
 M.print();
cout<<"请输入要插入的学生学号，姓名，成绩1，成绩2"<<endl;
cin>>b>>e>>s1>>s2;
M.push(b,y,s1,s2);
cout<<"输出顺序栈表为"<<endl;
 M.print();
 }
实验6      利用顺序存储结构存储队列时队列抽象数据类型的实现。要求数据元素为学号、姓名、年龄、总分四个域。
实验六
#include<iostream.h>
#include<stdlib.h>
#include<string.h>
const int length=8;
typedef char ZF[15];
template<class A1,class A2,class A3>class list;
template<class A1,class A2,class A3>class circle{
friend class list<A1,A2,A3>;
private:
	ZF name;
	A1 num;
	A2 age;
	A3 sco;
};
template<class A1,class A2,class A3>class list{
	public:
		list();
		int build(A1 e1,ZF e,A2 e2,A3 e3);
		void print();
		int getlength();
	private:
		circle<A1,A2,A3> *base;
		int begin;
		int end;
};
template<class A1,class A2,class A3>
list<A1,A2,A3>::list(){
base=new circle<A1,A2,A3>[length];
begin=0;
end=0;
}
template<class A1,class A2,class A3>
int list<A1,A2,A3>::build(A1 e1,ZF e,A2 e2,A3 e3)
{
	if((end+1)%length==begin)
		return 0;
	((base[end]).num)=e1;
	strcpy((base[end]).name,e);
	((base[end]).age)=e2;
	((base[end]).sco)=e3;
	end=((end+1)%length);
	return 1;
}
template<class A1,class A2,class A3>
void list<A1,A2,A3>::print(){
int r;
for(r=begin;r!=end;r=((r+1)%length))
{
	cout<<((base[r]).num)<<" "<<((base[r]).name)<<" "<<((base[r]).age)<<" "<<((base[r]).sco)<<endl;
}}
template<class A1,class A2,class A3>
int list<A1,A2,A3>::getlength(){
return end;
}
void main(){
	list<int,int,int> k;
	int a,b,c,d;
	ZF f;
    cout<<"请输入学生个数"<<endl;
	cin>>a;
	cout<<"请输入学生学号，姓名，年龄，成绩"<<endl;
	for(int i=0;i<a;i++){
		cin>>b>>f>>c>>d;
		k.build(b,f,c,d);
	}
	cout<<"打印出学生信息"<<endl;
	k.print();
		cout<<"请输入要添加的学生信息"<<endl;
		cin>>b>>f>>c>>d;
		k.build(b,f,c,d);
cout<<"打印出学生信息"<<endl;
	k.print();
cout<<"打印出学生人数"<<endl;
cout<<k.getlength()<<endl;
}

实验七
#include <iostream.h>
#include <stdio.h>
#include <assert.h>
template <class A1,class A2,class A3,class A4> class Queue;
template <class A1,class A2,class A3,class A4> class QueueNode {	
friend class Queue<A1,A2,A3,A4>;
private: 
    A1 xuehao;
	A2 name;
A3 age;
A4 score;//队列结点数据
    QueueNode<A1,A2,A3,A4> *link;  //结点链指针
};    
template <class A1,class A2,class A3,class A4> class Queue {	
public: 
    Queue ( ) { rear=front=NULL; }
    ~Queue ( );						
    void EnQueue (A1 I1,A2 I2,A3 I3,A4 I4 );
    void DeQueue (A1 &e1,A2 &e2,A3 &e3,A4 &e4 );    
    void GetFront (A1 &e1,A2 &e2,A3 &e3,A4 &e4 );					
    void MakeEmpty ( ) { front = rear ; }
    int IsEmpty ( ) { return  front->link == NULL; }
	void prn();
	void cre(int n);
private: 
    QueueNode<A1,A2,A3,A4> *front, *rear; //队列指针
};
template <class A1,class A2,class A3,class A4> Queue<A1,A2,A3,A4>::~Queue ( ) {
                       //队列的析构函数
   QueueNode<A1,A2,A3,A4> *p;
    while ( front != NULL ) {	
                      //逐个结点释放
        p = front;  front = front->link;  delete p;
    }
}
template <class A1,class A2,class A3,class A4> void Queue<A1,A2,A3,A4>:: EnQueue (A1 I1,A2 I2,A3 I3,A4 I4 ) {
//将新元素I1插入到队列的队尾 
    if ( front->link == NULL )
	{front->link = rear = new QueueNode<A1,A2,A3,A4>;
	rear->xuehao=I1;rear->name=I2; rear->age=I3; rear->score=I4;rear->link=NULL;}
    else 
	{rear = rear->link = new QueueNode<A1,A2,A3,A4>;
	rear->xuehao=I1;rear->name=I2; rear->age=I3; rear->score=I4;rear->link=NULL;}
}
template <class A1,class A2,class A3,class A4> void Queue<A1,A2,A3,A4>::DeQueue (A1 &e1,A2 &e2,A3 &e3,A4 &e4) {
//删去队头结点，并返回队头元素的值
    assert ( !IsEmpty ( ) );	//判队空的断言
    QueueNode<A1,A2,A3,A4> *p = front->link;		
    e1=p->xuehao;e2=p->name; e3=p->age; e4=p->score;	//保存队头的值
     front->link= p->link;    //新队头
    if (p==rear)  rear=front;   
    delete p;	 
   		
}
template <class A1,class A2,class A3,class A4> void Queue<A1,A2,A3,A4>::GetFront (A1 &e1,A2 &e2,A3 &e3,A4 &e4 ) {
//若队不空，则函数返回队头元素的值; 
//若队空，则函数返回0。
    assert ( !IsEmpty ( ) );			
 e1=front->link ->xuehao;e2=front->link ->name; e3=front->link ->age;e4=front->link ->score;	}
template <class A1,class A2,class A3,class A4> void Queue<A1,A2,A3,A4>::prn( ) {
   QueueNode<A1,A2,A3,A4> *p = front->link;
   while(p!=NULL)
   {
	   cout<<"("<<p->xuehao<<" "<<p->name<<" "<<p->age<<" "<<p->score<<")"<<" ";
       p=p->link;
   }
   cout<<endl;
}
template <class A1,class A2,class A3,class A4> void Queue<A1,A2,A3,A4>::cre(int n) {
   QueueNode<A1,A2,A3,A4> *p;
   front=rear=new QueueNode<A1,A2,A3,A4>;
   front->link=NULL;
   for(int i=n;i>0;--i)
     {
	   p=new QueueNode<A1,A2,A3,A4>;
	   cin>>p->xuehao>>p->name>>p->age>>p->score;
	   p->link=NULL;
	   rear->link=p;rear=p;
   }
   
}
void main()
{
	Queue <int,char,int,int > M;
	int k,x1,x3,x4,a1,a3,a4,b1,b3,b4;
	char x2,a2,b2;
	cin>>k;
	M.cre(k);
	M.prn();
    M.DeQueue(A1,A2,A3,A4);
	cout<<a1<<" "<<a2<<” “<<a3<<” ”<<a4<<endl;
	M.prn();
	cout<<"x1=";
	cin>>x1;
    cout<<"x2=";
	cin>>x2;
cout<<"x3=";
	cin>>x3;
cout<<"x4=";
	cin>>x4;
	M.EnQueue(x1,x2,x3,x4);
    M.GetFront(b1,b2,b3,b4);
	cout<<b1<<" "<<b2<<” “<<b3<<” “<<b4<<endl;
    M.prn();
}
