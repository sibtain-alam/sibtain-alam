- 👋 Hi, I’m @sibtain-alam
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
sibtain-alam/sibtain-alam is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import java.util.*;
class Main {
	public static void main(String args[]) {
		Scanner sc = new Scanner(System.in);
	int n = sc.nextInt();
     for(int i = 1;i<=n;i++){
		 for(int j =1;j<i;j++){
		 System.out.print(" ");
		 
		 }
		  for(int j =1;j<=2*n-2*i+1;j++){
		 System.out.print("*");
		 }System.out.println();
	 }
       for(int i = 1;i<=n;i++){
		 for(int j =1;j<=n-i;j++){
		 System.out.print(" ");
		 }
		  for(int j=1;j<=2*i-2*n+5;j++){
		 System.out.print("*");
		 }System.out.println();
	 }

		
         
	}	
}	
