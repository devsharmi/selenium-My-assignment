package week1.day3;

import java.util.Arrays;

public class PracticeArray {

	public static void main(String[] args) {
		int a[]= {3,2,5,6,11,8,9};
		int b[]= {1,3,5,7,9,11,13};
		Arrays.sort(a);
		Arrays.sort(b);
		for (int i = 0; i < a.length-1; i++) {
			for (int j = 0; j < b.length; j++) {
				if (a[i]==b[j]) {
				System.out.println (b[i]);	
				}
				
			}
		}

	}

}

