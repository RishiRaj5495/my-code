# my-code
My name is Rishi Raj 
I am from Prayagraj

class SumPair{
public static void main(String args[]){
int[] arr = {7,11,34,56};
int target  = 11, i = 0,j = arr.length-1,ps;
while (i < j) {
    ps = arr[i] + arr[j];
   if (ps > target)
   j--;
   else if(ps < target)
   i++;
   else{
   System.out.format("%d pair is %d , %d",ps, i,j);
   return;}
}


}
}
