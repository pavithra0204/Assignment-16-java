//bubble sort 


 import java.io.*;

 class bubblesort
  {
     public static void main(String[] args)
      {
         int [] num = {10,80,40,77,65,83,22,37};
         
         for(int i=0;i<num.length-1;i++)
          {  
              for(int j=0;j<num.length-1-i;j++)
                {

                   if(num[j] > num[j+1])
                     {
                        int temp = num[j];
                        num[j] = num[j+1];
                        num[j+1] = temp;
                      }
                  }
           }
    

          System.out.println("Sorted Array: ");

          for(int i=0;i<num.length;i++)
           {
                 System.out.print(num[i] + " ");
            }
       }
  }

 
