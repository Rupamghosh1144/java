# java
import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         System.out.print("Input: ");
//         int arr[] = new int[3];
        
//         // Taking input
//         for(int i = 0; i < 3; i++) {
//             arr[i] = sc.nextInt();
//         }
        
//         // Printing in reverse order, skipping if the third integer is 0
//         System.out.print("Output: Number in reverse order: ");
//         for(int i = 2; i >= 0; i--) {
//             if(i == 2 && arr[i] == 0) {
//                 continue; // if the third integer is 0, skip printing it
//             } else {
//                 System.out.print(arr[i]); // print the current element
//             }
//         }
        
//         sc.close(); // close the scanner
//     }
// }



// public class Main{
//     public static void main(String[] args){
//         Scanner sc=new Scanner(System.in);
//         System.out.print("input: ");
//         int arr[]=new int[6];
//         for(int i=0;i<6;i++){
//             arr[i]=sc.nextInt();
//         }
//         int sum=0;
        
        
//         for(int i=0;i<6;i++){
//             if(arr[i]%2==0){
//                 sum=sum+arr[i];
//             }
//         }
//         System.out.print("Output: "+sum+"(");
//         for(int i=0;i<=5;i++){
//             if(arr[i]%2==0){
                
//                 System.out.print(arr[i]+"+");
//             }
//         }
//         System.out.print(")"+sum);
//     }
// }



// import java.util.Scanner;

// public class Main {
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         System.out.print("input: ");
//         int arr[] = new int[6];
//         for (int i = 0; i < 6; i++) {
//             arr[i] = sc.nextInt();
//         }
//         int sum = 0;

//         for (int i = 0; i < 6; i++) {
//             if (arr[i] % 2 == 0) {
//                 sum = sum + arr[i];
//             }
//         }
//         System.out.print("Output: " + sum + "(");
//         boolean first = true; // Flag to handle '+' printing
//         for (int i = 0; i <= 5; i++) {
//             if (arr[i] % 2 == 0) {
//                 if (!first) {
//                     System.out.print("+");
//                 }
//                 System.out.print(arr[i]);
//                 first = false; // After printing the first even number, set it to false
//             }
//         }
//         System.out.print(")" + sum);
//     }
// }


// public class Main{
//     public static void main(String[] args){
//         Scanner sc=new Scanner(System.in);
//         int pizza=100;
//         int puffs=20;
//         int cold=10;
        
        
//         System.out.print("Enter the no of pizzas bought: ");
//         int pi=sc.nextInt();
//         System.out.print("Enter the no of puffs bought: ");
//         int pu=sc.nextInt();
//         System.out.print("Enter the no of cool drinks bought: ");
//         int c=sc.nextInt();
        
        
//         int total=(pizza*pi)+(puffs*pu)+(cold*c);
//         System.out.println("Bill Details");
//         System.out.print("No of pizzas: "+pi);
//         System.out.println();
//         System.out.print("No of Puffs: "+pu);
//         System.out.println();
//         System.out.print("No of cool drinks: "+c);
//         System.out.println();
//         System.out.print("Total Price="+total);
//         System.out.println();
//         System.out.print("ENJOY THE SHOW!!!");
        
        
//     }
// }



// public class Main{
//     public static void main(String[] args){
//         Scanner sc=new Scanner(System.in);
        
//         System.out.println("Enter the digits: ");
//         int a=sc.nextInt();
//         int b=sc.nextInt();
//         int c=sc.nextInt();
//         int d=sc.nextInt();
        
        
//         char p=(char)a;
//         char q=(char)b;
//         char r=(char)c;
//         char s=(char)d;
        
//         System.out.println();
//         System.out.println(a+"-"+p);
//         System.out.println(b+"-"+q);
//         System.out.println(c+"-"+r);
//         System.out.println(d+"-"+s);
        
//     }
// }




// public class Main{
//     public static void main(String[] args){
//         Scanner sc=new Scanner(System.in);
        
//         System.out.println("Enter the no of liters to fill the tank");
//         int tank=sc.nextInt();
//         if(tank<0){
//             System.out.print(tank+" is an invalid input");
//             return;
//         }
        
//         System.out.println("Enter the distance covered");
//         int dist=sc.nextInt();
//         if(dist<=0){
//             System.out.print(dist+" is an invalid input");
//             return;
//         }
//         int a=tank/dist;
//         double ans=(tank*100.0)/dist;
//         double gal=(tank*0.2642);
//         double miles=dist*0.6214;
//         double ans2=miles/gal;
        
//         System.out.println("Liters/100KM");
//         System.out.printf("%.2f",ans);
//         System.out.println();
//         System.out.println("Miles/gallons");
//         System.out.printf("%.2f",ans2);
        
//     }
// }



    
