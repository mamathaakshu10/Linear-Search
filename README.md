# Linear-Search
(C-Program)
#include<stdio.h>
int main()
{
    int n,even_sum=0,odd_sum=0,key,flag;
    printf("Enter the size of array:");
    scanf("%d",&n);
    printf("Enter the key:");
    scanf("%d",&key);
    int arr1[n];
    for(int i=0;i<=n-1;i++)
    {
        scanf("%d",&arr1[i]);
        if(arr1[i]==key)
        {
            flag=1;
            break;
        }
    }  
    if(flag==0)
      printf("key is found\n");
    else 
      printf("key is not found\n");
      
}
