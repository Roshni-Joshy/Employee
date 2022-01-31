# Employee
#Name,Year of joining,Salary,Address

public class Employee {
	String name =" ";
	int yrjoin,salary;
    String address=" ";
	public static void main(String[] args) {
		Employee E1= new Employee();
		E1.name="Robert";
		E1.yrjoin=1994;
		E1.salary=2000;
		E1.address="64C- WallsStreet";	
		System.out.println("Name:"+E1.name+"Year of joining:"+E1.yrjoin+"Salary:"+E1.salary+"Address:"+E1.address);
		Employee E2= new Employee();
		E2.name="Sam";
		E2.yrjoin=1994;
		E2.salary=4000;
		E2.address="68D- WallsStreet";	
		Employee E3= new Employee();
		System.out.println("Name:"+E2.name+"Year of joining:"+E1.yrjoin+"Salary:"+E1.salary+"Address:"+E1.address);
		E3.name="John";
		E3.yrjoin=1999;
		E3.salary=3000;
		E3.address="26B- WallsStreet";
		System.out.println("Name:"+E1.name+"Year of joining:"+E1.yrjoin+"Salary:"+E1.salary+"Address:"+E1.address);

	}

}

