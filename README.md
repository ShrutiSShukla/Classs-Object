# Classs-Object
Classs&amp;Object
public class Employee 
{
     String name;
    int year_of_joining;
    double salary;
    String address;
    
    void  initInfo(String n,int y,double s,String ad)
    {
            name=n;
            year_of_joining=y;
            salary=s;
            address=ad;
    }
    
    void displayInfo()

    {
        System.out.println("Employee Name: " +name);
        System.out.println("Employee joining year: " +year_of_joining);
        System.out.println("Employee Salary: " +salary);
        System.out.println("Employee Salary: " +address);
    }

	public static void main(String[] args) 
	{
        System.out.println("Employee-1 Detail");    
	Employee e1 = new Employee();
	e1.initInfo("Robert",1994 ,40000,"64C- Walls Streat" );
	e1.displayInfo();
        System.out.println("------------");
        System.out.println("Employee-2 Detail"); 
        Employee e2 = new Employee();
        e2.initInfo("Sam",2000,43000.55,"68D- Walls Streat");
	e2.displayInfo();
        System.out.println("------------");
        System.out.println("Employee-3 Detail"); 
        Employee e3 = new Employee();
        e3.initInfo("John",1999,50000,"26B- Walls Streat");
	e3.displayInfo();
		
	}
}
