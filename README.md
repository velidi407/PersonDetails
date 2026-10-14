import java.util.Scanner;
public class PersonDetails 
{
    public static void main(String[]args) 
    {

        Scanner sc = new Scanner(System.in);

        System.out.println("PERSON DETAILS");

        System.out.print("Enter Name: ");
        String name = sc.nextLine();

        System.out.print("Enter Date of Birth (DD-MM-YYYY): ");
        String dateOfBirth = sc.nextLine();

        System.out.print("Enter Age: ");
        int age = sc.nextInt();
        sc.nextLine();

        System.out.print("Enter Occupation: ");
        String occupation = sc.nextLine();

        System.out.print("Enter Mobile Number: ");
        String mobileNumber = sc.nextLine();

        System.out.print("Enter Aadhaar Number: ");
        String aadhaarNumber = sc.nextLine();

        System.out.println(" PERSON INFORMATION");
        System.out.println("Name          : " + name);
        System.out.println("Date of Birth : " + dateOfBirth);
        System.out.println("Age           : " + age);
        System.out.println("Occupation    : " + occupation);
        System.out.println("Mobile Number : " + mobileNumber);
        System.out.println("Aadhaar Number: " + aadhaarNumber);

        sc.close();
    }
}
