# Test
To learn Git
package Java;

public class constructorOverloading {
	
	String draw;
	
   constructorOverloading(){
    	System.out.println("Draw object is created");
		
	}
    constructorOverloading(String todraw){
    	draw=todraw;
    	System.out.println("Drawing : "+todraw );
    	 
	}
	
    public static void main(String[] args) {
    	
    	constructorOverloading overloading1=new constructorOverloading();
    	
    	constructorOverloading overloading2=new constructorOverloading("circle");
	}

}
