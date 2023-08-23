# Subarrayproblems
public class Main {
  public static void main(String[] args) {
    int arr[]={1,2,3,4,5};
    int n=arr.length;
   // print all subarray
      for(int i=0; i<n; i++){
        for(int j=i; j<n; j++){
          for(int k=i; k<=j; k++){
            System.out.print(arr[k]+" ");
          }       
     System.out.println();
    }
}   
}
}                              
       //print subarray sum// 1 2 3 4
    for(int i=0; i<n; i++){
      int sum=0;
      for(int j=i; j<n; j++){
          sum+=arr[j];
          System.out.print(sum+" ");
    }
  }   
}
}
         //print all subarray sum  
  for(int i=0; i<n; i++){
      for(int j=i; j<n; j++){
        int sum=0;
        for(int k=i; k<=j; k++){
          sum+=arr[k];
    }
     System.out.println(sum);
    }
   }   
  }
}
//max subarray sum
int max=0;
  for(int i=0; i<n; i++){
      for(int j=i; j<n; j++){
        int sum=0;
        for(int k=i; k<=j; k++){
          sum+=arr[k];
          max=Math.max(max,sum);
    }
    
}
} 
System.out.println(max);  
}
}
 //count of even length subarray with sum>=B
 int arr[]={1,2,3,4};
 int B=3;
 int count=0;
 for(int i=0; i<n; i++){
  int sum=0;
  for(int j=i; j<n; j++){
    int l=j-i+1;
      sum=sum+arr[j];
    if(l%2==0 && sum>=B){
      count++;
    }
   }

 }
 System.out.println(count);
 }
 }

//number of subarray sum which are even
 int count=0;
 for(int i=0; i<n; i++){
  int sum=0;
  for(int j=i; j<n; j++){
      sum=sum+arr[j];  
      if(sum%2==0){
        count++;
      }     
     }

 }
 System.out.println(count);
 }
 }



