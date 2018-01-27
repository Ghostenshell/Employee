import java.util.ArrayList;
import java.util.Scanner;

public class testManagerEmployee {

	public static void main(String[] args) {
		//Scanner to ask for string in next line
		Scanner scan = new Scanner(System.in);
		//local variables that need to be changed
		String employee = "";
		String salary = "";
		String department = "";
		
		//calling the Manager class.  Can be called again as tester2 if needed.
		Manager tester1 = new Manager();
		
		//set variables or arguments in the Manager/Employee class
		tester1.setName("Adrian");
		tester1.setSalary("$1,000");
		tester1.setDepartment("Housing");
		System.out.println(tester1.toString()+ ".  " + "He is in " + tester1.getDepartment());	
		//This is only a Test
		System.out.println("");
		System.out.println("This is only a test");
		System.out.println("");
		
		
		//Ask for employee name, salary, and department.  Figure out how to get "$" in employee class without changing employee class.
		System.out.println("Please enter the employees name:  ");
		employee = scan.nextLine();
		
		System.out.println("Please enter the employees name:  ");
		salary = scan.nextLine();
		
		System.out.println("Please enter the employees name:  ");
		department = scan.nextLine();
		//Enter the above into an array.  Can do/while loop to ask for more records.  Output records to a file.  See Chapt 7.
		
		ArrayList<String> records = new ArrayList<String>();
		records.add(employee);
		records.add(salary);
		records.add(department);
		//Test array and figure out how to manipulate.
		System.out.println(records);
		

		 
		//figured out that the above test is no longer needed.  Kept for testing purposes.  The string variable can be entered directly into tester1.
		tester1.setName(employee);
		tester1.setSalary(salary);
		tester1.setDepartment(department);
		
		
		System.out.println(tester1.toString()+ ".  " + "He is in " + tester1.getDepartment());
		
		
		
		
		
		
	scan.close();	
	}

}
