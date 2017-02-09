# Reverse-String-by-Word-using-Split
Split String and reverse any sentence



import java.util.*;


public class nameOne
{



	public static void main (String [] args)
	{
		String reverseThis = "Eeverything is going to get reversed!!!";
		String[] split = reverseThis.split(" ");
		
		String [] array1 = new String[split.length+1];
		int j= 0;
		
		for(int i = split.length-1; i>=0; i--){
			array1[j]=split[i];
			j++;
		}
		
		//Printed in a column format
		for(int i = 0; i<array1.length-1; i++){
			System.out.println(array1[i]);
		}
		//Printed in array formant []
		System.out.println(Arrays.toString(array1));
		//Printed like a normal sentence
		for(int i = 0; i<array1.length-1; i++ ) {
			 System.out.print(array1[i] + " ");
			}
	}
}
