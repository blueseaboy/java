//云课堂昵称mooceveryday

import java.util.Scanner;
public class num {
	public static void main(String[] args) {
		int num=0;
		System.out.println("请输入一个三位数：");
		Scanner input=new Scanner(System.in);
		num=input.nextInt();
		if(num>99 && num<1000){
			System.out.println("输出结果是："+num%10+num/10%10+num/100);
		}else{
			System.out.println("您输入的数字不是三位数，请重新输入");
		}
	
	}
	

}
