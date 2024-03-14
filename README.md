******************Function without name , type & modifier is known as Anonymous function.************

public void m1() {
	System.cout.println()
} 

******************converting above function to the Anonymous function.*****************

1. removing name here

	 public void () {
		System.out.println("TEST");
	} 

2. removing type here

	public () {
		System.out.println("TEST");
	} 


3. removing modifier here

	() {
		System.out.println("TEST");
	} 

4. final method become

	() {System.out.println("TEST");}

5. To convert above syntax to lambda expression, we have to add the arrow [->] symobl.

	() -> {System.out.println("TEST");}

6. for the single statement, we can remove curly braces.

	() -> System.out.println("TEST");
	

*******************YOU CAN CHECK THE README2.md FILE FOR THE RETURN TYPE METHOD***************************

