```java

/this is the link to the java problem:http://moringa-android.herokuapp.com/
package janeK;
import java.util.Scanner;
public class ClassjaneK {

	public static void main(String [] args){
		Scanner scannerj = new Scanner (System.in);
		
		//this are the qualities JaneK is considering
		String a="He is above 26 yrs old";
		String b="He is working";
		String c="He does physical exercises";
		String d="He is an asshole";
		String e="He lives alone";
		String f="He loves pets";
		String g="He has brown shoes";
		String h="He has a carpet in the house";
		
		String[] vars1={a,b,c,d,e,f,g,h};
		
		//this loop iterates thru the qualities and stores the responses in an array
		for(int i=0;i<vars1.length;i++){
			System.out.println(vars1[i]);
			int response=scannerj.nextInt();
			
		}
		
