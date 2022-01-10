# Java_Core
package objectcreation;

public class Bike {
String engNumm;
String ownerName;
String bikeNum;

void ownerName(String ownerName)
{
this.ownerName=ownerName;
}

void whoistheowner()
{
System.out.println("Owner name is:"+ownerName);

}

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
	Bike pulser=new Bike();
	pulser.ownerName("Vishwambhar");
	pulser.whoistheowner();
	
	Bike pept =new Bike();
	pept.ownerName("Ankita");
	pept.whoistheowner();
	

	}

}
