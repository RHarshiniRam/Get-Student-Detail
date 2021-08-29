# Get-Student-Detail
To print student details
import java.util.Scanner; 
public class GetStudentDetails 
{ 
public static void main(String args[])
{ 
String name; 
int roll, mat,phy,chem,tam;
Scanner sc=new Scanner(System.in); 
System.out.print("Enter Name: "); 
name=sc.nextLine(); 
System.out.print("Enter Roll Number: ");
roll=sc.nextInt();
System.out.print("Enter marks in Maths , Physics , Chemistry and Tamil: "); 
mat=sc.nextInt();
phy=sc.nextInt();
chem=sc.nextInt(); 
tam=sc.nextInt(); 
int total=mat+phy+chem+tam; 
System.out.println("Roll Number:" + roll +"\tName: "+name); 
System.out.println("Marks (Maths, Physics, Chemistry,Tamil): " +mat+","+phy+","+chem+","+tam); 
}
}

