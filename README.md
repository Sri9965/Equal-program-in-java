# Srivelan
import java.util.Arrays;
public class Main
{
	public static void main(String[] args) {
	    int[] array1 = {1,2,3};
	    int[] array2 = {1,2,3};
	    int[] array3 = {4,5,6};
	    
	    boolean equals1and2 = Arrays.equals(array1,array2);
	     boolean equals1and3 = Arrays.equals(array1,array3);
	    
		System.out.println("array1 equal array2?" + equals1and2);
		System.out.println("array1 equal array3?" + equals1and3);
	}
}
