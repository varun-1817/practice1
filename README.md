# program to reverse an array
#array_programs
package work_placement;

public class arrayreverse{

	static void reversearray(int arr[], int start, int end) {
		int temp;
		while(start<end) {
			temp = arr[start];
			arr[start] = arr[end];
			arr[end ]= temp;
			start++;
			end--;
		}
		}
	static void printarray(int arr[], int size) {
		for(int i = 0; i<size; i++) 
			System.out.print(arr[i]+" ");
			System.out.println();
	}
	
	public static void main(String args []) {
		int [] arr = {1,2,3,4,5,6};
		printarray(arr,6);
		reversearray(arr,0,5);
		System.out.println("reverse array is");
		printarray(arr,6);
		
	}
}
