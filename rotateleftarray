# rotate leftarray

package work_placement;

import java.io.*;

public class arrayleftrotation {
	static void rotate(int arr[], int d, int n) {
		int temp[] = new int[n];
		int k=0;
		for(int i=d;i<n;i++) {
			temp[k]= arr[i];
			k++;
		}
		
		for(int i=0;i<d;i++) {
			temp[k] = arr[i];
			k++;
		}
		for(int i=0;i<n;i++) {
			arr[i] = temp[i];
		}
	}
	
	static void printarray(int arr[], int n) {
	  for(int i=0;i<n;i++) {
		  System.out.print(arr[i]+" ");
	  }
	}
	
	public static void main(String args []) {
		int [] arr = {1,2,3,4,5,6,7};
		int n= arr.length;
		int d=2;
		rotate(arr, d, n);
		printarray(arr, n);
		
	}
}



