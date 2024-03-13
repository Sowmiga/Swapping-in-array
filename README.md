# Swapping-in-array
I have a done a program in SWAPPING IN ARRAY using java programming language.

import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();
	    int temp;
	    int a[]=new int[n];
	    for(int i=0;i<n;i++){
	        a[i]=sc.nextInt();}
	        for(int i=0;i<n-1;i+=2){//swap the numbers
	            temp=a[i];
	            a[i]=a[i+1];
	            a[i+1]=temp;
	        }
	        for(int i=0;i<n;i++){//print the output
	        System.out.print(a[i]+" ");}
	}
}
