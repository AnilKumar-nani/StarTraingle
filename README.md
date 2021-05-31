# StarTraingle

My requirement is to print the startraingle 

i need to take the input from the user so that i took the scanner class

          Scanner sc = new Scanner(System.in);
          System.out.println("enter n value");
          int n = sc.nextInt();
 i took the outer for loop to print the number of rows need
                 
        for(int i=0;i<n;i++)
 
 and  to print the star and space , i took the nested for loop 
 
     for(int j=0;j<n-i-1;j++)
            {
              System.out.print(" ");
            }
            for(int k=0;k<2*i+1;k++)
            {
              System.out.print("*");
            }
            System.out.println();
