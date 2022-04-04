# Array-Sorted-or-Not
 public class Array_Sorted_Or_Not {
        public static void main(String[] args)
        {
            System.out.println("Find that array is Sorted or Not:");
            System.out.println("Enter the no of elements in the matrix :");
            Scanner sc = new Scanner(System.in);
            int num = sc.nextInt();
            int arr[] = new int[num];
            System.out.println("Enter the elements in the array :");
            for(int i=0; i<num; i++)
            {
                arr[i] = sc.nextInt();
            }
            System.out.println("Printing the array :");
            for (int j=0; j<num; j++)
            {
                System.out.print(arr[j]);
                System.out.print(" ");
            }
            System.out.println();
            Arrays.sort(arr);
            System.out.println("Printing the array after sorting :");
            for(int i=0; i<num; i++)
            {
                System.out.print(arr[i]);
                System.out.print(" ");

        }
    }

}
