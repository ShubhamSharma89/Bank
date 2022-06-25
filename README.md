package Bank;

import java.util.*;

public class Student {
	
	
	String name;
	
	String fname;
	
	public static void main(String[] args) {
		
	
	Scanner sc = new Scanner(System.in);
	System.out.println("enter no. of students");
	int a= sc.nextInt();
	Student s[]= new Student[a];

	for(int i=0;i<s.length;i++)
	{
		s[i]= new Student();
		System.out.println("enter name ");
		String name= sc.next();
		s[i].name = name;
		
		System.out.print("father name");
		s[i].fname = sc.next();
	}


	}
	
}
