# Employee
public class Employee
{
    int emp_id;
    String emp_name;
    int emp_sal;

    void setEmp_id(int emp_id)
    {
        this.emp_id=emp_id;

    }
    int getEmp_id()
    {
        return emp_id;
    }
    void setEmp_name(String emp_name)
    {
        this.emp_name=emp_name;
    }
    String getEmp_name()
    {
        return emp_name;
    }
    void setEmp_sal(int emp_sal)
    {
        this.emp_sal=emp_sal;
    }
    int getEmp_sal()
    {
        return emp_sal;
    }
}


# Main
public class Main {
    public static void main(String[] args) {
        Employee e1=new Employee();
        e1.setEmp_id(101);
        e1.setEmp_name("sneha");
        e1.setEmp_sal(1000);

        System.out.println("emp id is="+e1.getEmp_id());
        System.out.println("emp name is="+e1.getEmp_name());
        System.out.println("emp sal is="+e1.getEmp_sal());
    }
}
