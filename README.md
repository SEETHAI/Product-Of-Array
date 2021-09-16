# Product-Of-Array
Java program to find the Product Of Array
public class ProductOfArray {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args)
    {
        int[] arr=new int[]{1,5,3,6,8};
       
             int Product=1;
               for(int i=1; i<arr.length;i++) {
           Product=Product+arr[i];
                }
                  System.out.println("Product of all the elements of an array:"+Product);
               
                }
