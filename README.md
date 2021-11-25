# Palindrom-Say-lar

package methods;

public class palindromSayılar {
	
	static boolean isPolidrom(int input){
		int tmp,tersSayı=0,kalan;
		tmp=input;
		while(tmp !=0) {
			kalan=tmp%10;
			tersSayı=tersSayı*10+kalan;
			tmp/=10;
			
			
			
		}
		if(input==tersSayı) {
			return true;
		}else
		return false;
	}

	public static void main(String[] args) {
		//Polindrom sayılar= ortadan ikiye böldüğünde tersi kendine eşit olan sayılar..   123321veya121
		System.out.println(isPolidrom(123321));
		
		
		
	
	
		
		
		
		
		
		

	}

}
