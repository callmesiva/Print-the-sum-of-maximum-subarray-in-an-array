# Print-the-sum-of-maximum-subarray-in-an-array

      int arr[] = {6,-1,-2,-3,-4,-5};
      
      int add =0;
      int tol = 0;
      
      for(int  i=0; i<arr.length; i++)
      {  
         add=0;
        
        for(int j=i; j<arr.length; j++)
        {
          add=add+arr[j];
          if(add>tol)
          {
            tol=add;
          }
          
        }
      }  
      
      System.out.println(tol);
