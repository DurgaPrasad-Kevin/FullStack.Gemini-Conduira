# FullStack.Gemini-Conduira
A 6 weeks training by Gemini solutions on Java Full-Stack development 


//Source code for creating a thread and printing its name.

import java.util.*;

public class MyThread 
{	
	public static void main(String[] args) 
  {	
		//Creating a thread with name 'My First Thread'
		Thread t1 = new Thread("My First Thread");
		t1.start();
		
    //printing the name of the thread
		System.out.println(t1.getName());
	}
}
