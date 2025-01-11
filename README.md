# Fact-recursion
Public class recurfact {
static int fact(int n){
return(n&lt;=1) ? 1 : n * fact(n-1);
}
public static void main(String[]args){
System.out.println(fact(7));
}
}
OUTPUT:
5040
