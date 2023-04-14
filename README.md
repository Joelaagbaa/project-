


public class Student {
    private String name; 
    private int age;
    private String matriculationNumber;
    
    public Student(String name, int age, String matriculationNumber) {
        this.name = name;
        this.age = age;
        this.matriculationNumber = matriculationNumber;
    }
    
    public String getName() {
        return name;
    }
    
    public int getAge() {
        return age;
    }
    
    public String getMatriculationNumber() {
        return matriculationNumber;
    }
    
    public static void main(String[] args) {
        Student s1 = new Student("Nzor Emmanuel simeage", 23, "NA21/1209");
        Student s2 = new Student("Aagbaa Joel Paul", 20, "NA21/1185");
        Student s3 = new Student("John peter donald", 22, "NA21/1833");
        
        System.out.println("Student 1:");
        System.out.println("Name: " + s1.getName());
        System.out.println("Age: " + s1.getAge());
        System.out.println("Matriculation Number: " + s1.getMatriculationNumber());
        
        System.out.println("Student 2:");
        System.out.println("Name: " + s2.getName());
        System.out.println("Age: " + s2.getAge());
        System.out.println("Matriculation Number: " + s2.getMatriculationNumber());
        
        System.out.println("Student 3:");
        System.out.println("Name: " + s3.getName());
        System.out.println("Age: " + s3.getAge());
        System.out.println("Matriculation Number: " + s3.getMatriculationNumber());
    }
}


