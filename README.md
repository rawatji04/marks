# marks
import java.util.Scanner;

public class StudentMarks {     ///// divide division my student's percentage.....
    public static void main(String[] args) {
        int marks;
        System.out.println("enter percentage of student.....");
        Scanner obj=new Scanner(System.in);
        marks=obj.nextInt();

        if (marks>=60 && marks<=100)
            System.out.println("first division");
        if (marks<=59 && marks>=45)
            System.out.println("second division");
        if (marks>=33 && marks<=44)
            System.out.println("third division");
        else if (marks<33)
        System.out.println("failed.....");
        else
            System.out.println("invalid number bcz percentage can't be more then 100% please try valid percentage.");
    }

}
