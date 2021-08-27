# Get-Student-Detail
To print student details
import java.util.Scanner; 
public class GetStudentDetails 
{ 
public static void main(String args[])
{ 
String name; 
int roll, maths,physics,chemistry,tamil;
Scanner sc=new Scanner(System.in); 
System.out.print("Enter Name: "); 
name=sc.nextLine(); 
System.out.print("Enter Roll Number: ");
roll=sc.nextInt();
System.out.print("Enter marks in Maths , Physics , Chemistry and Tamil: "); 
maths=sc.nextInt();
physics=sc.nextInt();
chemistry=sc.nextInt(); 
tamil=sc.nextInt(); 
int total=maths+physics+chemistry+tamil; 
float perc=(float)total/400*100;
System.out.println("Roll Number:" + roll +"\tName: "+name); 
System.out.println("Marks (Maths, Physics, Chemistry,Tamil): " +maths+","+physics+","+chemistry+","+tamil); 
System.out.println("Total: "+total +"\tPercentage: "+perc);
}
}

