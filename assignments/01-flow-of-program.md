[Video Link](https://youtu.be/lhELGQAV4gg)

## Create flowchart and pseudocode for the following:

1. Input a year and find whether it is a leap year or not. ((year%4 == 0 && year%100 != 0) | year%400 == 0)
2. Take two numbers and print the sum of both. (sum = a+b)
3. Take a number as input and print the multiplication table for it. 
 [       for(int i=1; i<= 10; i++){
            System.out.println(n*i);
        }]
4. Take 2 numbers as inputs and find their HCF and LCM. [HOLD]
5. Keep taking numbers as inputs till the user enters ‘x’, after that print sum of all.



class Main {
    public static void main(String[] args) {
        System.out.println("Try programiz.pro");
        Scanner sc = new Scanner(System.in);
        String input = sc.next();
        int sum = 0;
        while(!input.equals("x") ){
            sum += Integer.parseInt(input) ;
            input = sc.next();
        }
        System.out.println("Sum: " + sum);
        
    }
}


