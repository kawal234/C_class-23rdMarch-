# C_class-23rdMarch-
#include<stdio.h>

//CASE-1: For entering and retrieving values from an Array
//int main(){
//	int a[5],i;
//	printf("Enter the Array Elements: ");
//	for(i=0;i<=5;i++){
//		scanf("%d",&a[i]);
//		
//	}
//	printf("The Array Elements are :");
//	for(i=0;i<=5;i++){
//		printf("\nArray Elements Are: %d ",a[i]);
//	}
//	return 0;
//}
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
//CASE-2
//int main(){
//	int a[5],i,sum=0;
//	printf("Enter the Values of Arrays: ");
//	for(i=0;i<=5;i++){
//		scanf("%d",&a[i]);
//		sum=sum+a[i];
//	}
//	printf("The Sum is : %d",sum);
//}
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
//CASE-3: Marks of 5 students in a Class for the Same subject

//int main(){
//	float a[5],sum=0.0f,avg=0.0f;
//	int i;
//	printf("Enter the Marks Obtained : ");
//	for(i=0;i<=5;i++){
//		scanf("%f",&a[i]);
//	}
//	for(i=0;i<=5;i++){
//		sum=sum+a[i];
//	}
//	avg=sum/5.0f;
//	printf("The Average Marks is %.2f and Total marks is %.2f",avg,sum);
//	return 0;
//	
//	
//}
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
//CASE-4 To count elements which are mutiple of 5

//int main(){
//	
//	int a[5],i,count=0;
//	printf("Enter the Numbers : ");
//	for(i=0;i<=5;i++){
//		scanf("%f",&a[i]);
//	}
//	for(i=0;i<=5;i++){
//		if(a[i]%5==0){
//			count++;
//		}
//	}
//	printf("The Count of Numbers are: %d",count);
//	return 0;
//	
//	
//}

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

//CASE-5 To replace the multiple of 3 with -99 values

//int main(){
//	
//	int a[5],i,count=0;
//	printf("Enter the Numbers : ");
//	for(i=0;i<=5;i++){
//		scanf("%f",&a[i]);
//	}
//	for(i=0;i<=5;i++){
//		if(a[i]%3==0){
//			a[i]=-99;
//		}
//	}
//	printf("The Updated Values are:");
//	for(i=1;i<5;i++){
//		printf("\n%d",a[i]);
//		}
//	
//	return 0;
//	
//	
//}

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

//CASE-6: To find the minimum and maximum number 

//int main(){
//	
//	int a[5],i,count=0,max,min;
//	printf("Enter the Numbers : ");
//	for(i=0;i<5;i++){
//		scanf("%d",&a[i]);
//	}
//	max=a[0];
//	min=a[0];
//	
//	for(i=1;i<5;i++){
//		if(a[i]>max){
//			max=a[i];
//		}
//		else if(a[i]<min){
//			min=a[i];
//		}
//	}
//	printf("Largest Number is: %d and Smallest Number is : %d",max,min);
//	
//}
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
