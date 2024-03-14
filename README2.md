******************Function without name , type & modifier is known as Anonymous function.************

	public int add(int a, int b){
	return a*b;
	}
	
	
******************converting above function to the Anonymous function.*****************

	
1. removing name here

	public int (int a, int b){
	return a*b;
	}
	
2. removing type here

	public  (int a, int b){
	return a*b;
	}


3. removing modifier here

	  (int a, int b){
	return a*b;
	}
 

4. final method become

	(int a, int b) {return a*b;}

5. To convert above syntax to lambda expression, we have to add the arrow [->] symobl.

	(int a, int b)-> {return a*b;}

6. we can remove the type from the parameters of the below method, 
   *******how the compiler identified the type you can seen in the program, serach AnonymousFunctionalProgramming project on my list ****

	(a,b)-> {return a*b;}
	
7. here, it's a single statement but to remove curly braces , we have to remove return key word from above sytax.
 
	 	(a,b)-> a*b;
 
8. whenever you want add the return statement, also must add the curly braces otherwise you will get error.	