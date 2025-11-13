# java
//课程经历代码
import java.util.Scanner;

public class aaa {
    public static void main(String[] args) {
        var sc = new Scanner(System.in);
        int age = sc.nextInt();
        if (age == 33)
            System.out.println("CCTV新闻频道");
        if (age == 31)
            System.out.println("CCTV体育频道");
        if (age == 30)
            System.out.println("CCTV中文国际");
        if (age == 27)
            System.out.println("CCTV综合");
        else
            System.out.println("选择的频道age频道不存在，请重新选择");
    }
}
