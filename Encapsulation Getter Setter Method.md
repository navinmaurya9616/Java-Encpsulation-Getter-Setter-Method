# javaPrograms
it's store of all programe which is done by me in JAVA from begining
package GetterSetter;

public class Encapsulation1 {
	String empname;
	int empage;
	int empid;
	public String getEmpName()
	{
		return empname;
		
	}
	public int getEmpAge()
	{
		return empage;
	}
	public  int getEmpId()
	{
		return empid;
	}
	public  void setEmpName(String setvalue)
	{
		empname=setvalue;
	}
	public void SetEmpAge(int setvalue)
	{
		empage=setvalue;
	}
	public void setEmpId(int setvalue)
	{
		empage=setvalue;
	}
	public class TestEncapsulation{
	}
	public static void main(String[] args) {
		Encapsulation1 en=new Encapsulation1();
		en.setEmpName("Navin");
		en.SetEmpAge(22);
		en.setEmpId(1234560);
		System.out.println("Employee Name:"+en.getEmpName());
		System.out.println("Employee Age:"+en.getEmpAge());
		System.out.println("Employee Id:"+en.getEmpId());
	}

}

