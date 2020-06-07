# Algorithom-lab
Assignment 
class BubbleSort
{
void bubbleSort(int a[])
{
int n = a.length;
for (int i = 0; i < n-1; i++)
for (int j = 0; j < n-i-1; j++)
if (a[j] > a[j+1])
{
// swap temp and arr[i]
int temp = a[j];
a[j] = a[j+1];
a[j+1] = temp;
}
}
void printArray(int x[])
{
int n = x.length;
for (int i=0; i<n; ++i)
System.out.print(x[i­] + " ");
System.out.println()­;
}
public static void main(String args[])
{
BubbleSort ob = new BubbleSort();
int array[] = {12,20,100,90,500,54­,24};
ob.bubbleSort(array)­;
System.out.println("­SORTED ARRAYS");
ob.printArray(array)­;
}
}
