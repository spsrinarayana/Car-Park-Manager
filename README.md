# Car-Park-Manager
This Program is done for Implement the Object Oriented Programming Techniques

## SLIITCarParkManager.java
  	public class SLIITCarParkManager implements CarParkManager  {
		static int i = 0;
 	
 		public static void main(String[] args) {
 			System.out.println("");
			System.out.println("//--------------------------------------------------------------------------------//");
			System.out.println("//-----------------___________________________________________--------------------//");
			System.out.println("//----------------|                                           |-------------------//");
			System.out.println("//----------------|     Welcome to SLIIT CAR PARK MANAGER     |-------------------//");
			System.out.println("//----------------|        By Sri Narayana S N B M S P        |-------------------//");
			System.out.println("//----------------|                  EN21475368               |-------------------//");
			System.out.println("//----------------|___________________________________________|-------------------//");
			System.out.println("//--------------------------------------------------------------------------------//");
			System.out.println("//--------------------------------------------------------------------------------//");
			System.out.println("");
	
	//Entering Taxi Three Wheeler - To Slot 1 (s1)-----------------------------------------------------------
		
		SLIITCarParkManager s1 = new SLIITCarParkManager();
			if(s1.vehilceEntered()) {
				
				ThreeWheeler v1 = new ThreeWheeler("Taxi","AAA-0897","TVS" );
				Date_Time d1 = new Date_Time("20th June 2022","12:50");
			}else{
				
		}
		System.out.println("	Slots empty    : " +s1.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s1.getNumOccupiedslots());
		System.out.println();

	//Entering NotForHire Three Wheeler - To Slot 2 (s2)------------------------------------------------------
		
		SLIITCarParkManager s2 = new SLIITCarParkManager();
			if(s2.vehilceEntered()) {
				
				ThreeWheeler v2 = new ThreeWheeler("NotForHire","ABC-3695","BAJAJ" );
				Date_Time d2 = new Date_Time("8th January 2022","14:50");
			}else{
				
		}
		System.out.println("	Slots empty    : " +s2.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s2.getNumOccupiedslots());
		System.out.println();	
		
	//Entering Goods Van - To Slot 3 (s3)---------------------------------------------------------------------
		
		SLIITCarParkManager s3 = new SLIITCarParkManager();
			if(s3.vehilceEntered()) {
				
				Van v3 = new Van("Goods",8000,"NC-7798","TOYOTA");
				Date_Time d3 = new Date_Time("5th March 2022","11:50");	
			} else {
				
		}
		System.out.println("	Slots empty    : " +s3.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s3.getNumOccupiedslots());
		System.out.println();
	
	//Entering Passenger Van - To Slot 4 (s5)---------------------------------------------------------------------
	
		SLIITCarParkManager s4 = new SLIITCarParkManager();
			if(s4.vehilceEntered()) {
				
				Van v4 = new Van("Passenger",30,"PD-5843","NISSAN");
				Date_Time d4 = new Date_Time("9th January 2022","17:30");
			} else {
				
			}
		System.out.println("	Slots empty    : " +s4.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s4.getNumOccupiedslots());
		System.out.println();
	
	//Entering Red Car - To Slot 5 (s5)-----------------------------------------------------------------------
		
		SLIITCarParkManager s5 = new SLIITCarParkManager();
			if(s4.vehilceEntered()) {
				
				Car c5 = new Car(4,"Red","CAX-7788","TOYOTA");
				Date_Time d5 = new Date_Time("9th September 2022","13:50");
			} else {
				
			}
		System.out.println("	Slots empty    : " +s5.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s5.getNumOccupiedslots());
		System.out.println();
			
	//Entering Taxi Three Wheeler - To Slot 6 (s6)-----------------------------------------------------------
		
		SLIITCarParkManager s6 = new SLIITCarParkManager();
			if(s6.vehilceEntered()) {
				
				ThreeWheeler v6 = new ThreeWheeler("Taxi","ABB-0237","PIAGIO" );
				Date_Time d6 = new Date_Time("20th July 2022","04:45");
			}else{
				
		}
		System.out.println("	Slots empty    : " +s1.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s1.getNumOccupiedslots());
		System.out.println();

	//Entering NotForHire Three Wheeler - To Slot 7 (s7)------------------------------------------------------
		
		SLIITCarParkManager s7 = new SLIITCarParkManager();
			if(s7.vehilceEntered()) {
				
				ThreeWheeler v7 = new ThreeWheeler("NotForHire","ABC-3695","BAJAJ" );
				Date_Time d7 = new Date_Time("23th January 2022","14:56");
			}else{
				
		}
		System.out.println("	Slots empty    : " +s6.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s6.getNumOccupiedslots());
		System.out.println();	
		
	//Entering Goods Van - To Slot 8 (s8)---------------------------------------------------------------------
		
		SLIITCarParkManager s8 = new SLIITCarParkManager();
			if(s8.vehilceEntered()) {
				
				Van v8 = new Van("Goods",5000,"NA-7798","MICRO");
				Date_Time d8 = new Date_Time("2nd June 2022","12:20");	
			} else {
				
		}
		System.out.println("	Slots empty    : " +s7.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s7.getNumOccupiedslots());
		System.out.println();
	
	//Entering Passenger Van - To Slot 9 (s9)---------------------------------------------------------------------
	
		SLIITCarParkManager s9 = new SLIITCarParkManager();
			if(s9.vehilceEntered()) {
				
				Van v9 = new Van("Passenger",25,"NE-0000","BENZ");
				Date_Time d9 = new Date_Time("9th January 2022","17:30");
			} else {
				
			}
		System.out.println("	Slots empty    : " +s8.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s8.getNumOccupiedslots());
		System.out.println();
	
	//Entering Green Car - To Slot 10 (s10)-----------------------------------------------------------------------
		
		SLIITCarParkManager s10 = new SLIITCarParkManager();
			if(s10.vehilceEntered()) {
				
				Car c10 = new Car(2,"Green","CCC-2222","LAMBOGINI");
				Date_Time d10 = new Date_Time("9th September 2022","13:34");
			} else {
				
			}
		System.out.println("	Slots empty    : " +s9.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s9.getNumOccupiedslots());
		System.out.println();

	//Entering Taxi Three Wheeler - To Slot 11 (s11)-----------------------------------------------------------
		
		SLIITCarParkManager s11 = new SLIITCarParkManager();
			if(s11.vehilceEntered()) {
				
				ThreeWheeler v11 = new ThreeWheeler("Taxi","ABS-2323","BAJAJ" );
				Date_Time d11 = new Date_Time("20th June 2022","17:38");
			}else{
				
		}
		System.out.println("	Slots empty    : " +s11.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s11.getNumOccupiedslots());
		System.out.println();

	//Entering NotForHire Three Wheeler - To Slot 12 (s12)------------------------------------------------------
		
		SLIITCarParkManager s12 = new SLIITCarParkManager();
			if(s12.vehilceEntered()) {
				
				ThreeWheeler v12 = new ThreeWheeler("NotForHire","AAA-0001","PIAGIO" );
				Date_Time d12 = new Date_Time("8th January 2022","23:55");
			}else{
				
		}
		System.out.println("	Slots empty    : " +s12.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s12.getNumOccupiedslots());
		System.out.println();	
		
	//Entering Goods Van - To Slot 13 (s13)---------------------------------------------------------------------
		
		SLIITCarParkManager s13 = new SLIITCarParkManager();
			if(s13.vehilceEntered()) {
				
				Van v13 = new Van("Goods",1000,"NA-7798","MITSUBISHI");
				Date_Time d13 = new Date_Time("5th December 2022","23:50");	
			} else {
				
		}
		System.out.println("	Slots empty    : " +s13.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s13.getNumOccupiedslots());
		System.out.println();
	
	//Entering Passenger Van - To Slot 14 (s14)---------------------------------------------------------------------
	
		SLIITCarParkManager s14 = new SLIITCarParkManager();
			if(s14.vehilceEntered()) {
				
				Van v14 = new Van("Passenger",10,"PC-9876","BENZ");
				Date_Time d14 = new Date_Time("9th January 2022","17:12");
			} else {
				
			}
		System.out.println("	Slots empty    : " +s14.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s14.getNumOccupiedslots());
		System.out.println();
	
	//Entering Black Car - To Slot 15 (s15)-----------------------------------------------------------------------
		
		SLIITCarParkManager s15 = new SLIITCarParkManager();
			if(s14.vehilceEntered()) {
				
				Car c15 = new Car(4,"Black","KQ-9905","PORCHE");
				Date_Time d15 = new Date_Time("9th November 2022","13:50");
			} else {
				
			}
		System.out.println("	Slots empty    : " +s15.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s15.getNumOccupiedslots());
		System.out.println();
			
	//Entering Taxi Three Wheeler - To Slot 16 (s16)-----------------------------------------------------------
		
		SLIITCarParkManager s16 = new SLIITCarParkManager();
			if(s16.vehilceEntered()) {
				
				ThreeWheeler v16 = new ThreeWheeler("Taxi","AAA-8989","BAJAJ" );
				Date_Time d16 = new Date_Time("30th October 2022","14:43");
			}else{
				
		}
		System.out.println("	Slots empty    : " +s16.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s16.getNumOccupiedslots());
		System.out.println();

	//Entering NotForHire Three Wheeler - To Slot 17 (s17)------------------------------------------------------
		
		SLIITCarParkManager s17 = new SLIITCarParkManager();
			if(s17.vehilceEntered()) {
				
				ThreeWheeler v17 = new ThreeWheeler("NotForHire","ABC-1234","BAJAJ" );
				Date_Time d17 = new Date_Time("7th July 2022","12:46");
			}else{
				
		}
		System.out.println("	Slots empty    : " +s17.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s17.getNumOccupiedslots());
		System.out.println();	
		
	//Entering Goods Van - To Slot 18 (s18)---------------------------------------------------------------------
		
		SLIITCarParkManager s18 = new SLIITCarParkManager();
			if(s18.vehilceEntered()) {
				
				Van v18 = new Van("Goods",8000,"PD-4567","TOYOTA");
				Date_Time d18 = new Date_Time("5th June 2022","22:32");	
			} else {
				
		}
		System.out.println("	Slots empty    : " +s18.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s18.getNumOccupiedslots());
		System.out.println();
	
	//Entering Passenger Van - To Slot 19 (s19)---------------------------------------------------------------------
	
		SLIITCarParkManager s19 = new SLIITCarParkManager();
			if(s19.vehilceEntered()) {
				
				Van v19 = new Van("Passenger",43,"PE-1919","RENAULT");
				Date_Time d19 = new Date_Time("9th January 2022","17:30");
			} else {
				
			}
		System.out.println("	Slots empty    : " +s19.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s19.getNumOccupiedslots());
		System.out.println();
	
	//Entering Yellow Car - To Slot 20 (s20)-----------------------------------------------------------------------
		
		SLIITCarParkManager s20 = new SLIITCarParkManager();
			if(s20.vehilceEntered()) {
				
				Car c20 = new Car(4,"Yellow","CAC-1331","FERARI");
				Date_Time d20 = new Date_Time("19th September 2022","13:50");
			} else {
				
			}
		System.out.println("	Slots empty    : " +s20.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s20.getNumOccupiedslots());
		System.out.println();	

	//Entering White Car - Trying to enter-----------------------------------------------------------------------
		
		SLIITCarParkManager s21 = new SLIITCarParkManager();
			if(s21.vehilceEntered()) {
				
				Car c21 = new Car(4,"White","7788","BUGATTI");
				Date_Time d21 = new Date_Time("31st December 2022","23:59");
			} else {
				
			}
		System.out.println("	Slots empty    : " +s21.getNumEmptyslots());
		System.out.println("	Slots occupied : " +s21.getNumOccupiedslots());
		System.out.println();					
   
	}			
		
	public boolean vehilceEntered() {
		
		if(i<totalVehicleSlots) {											// checking whether there is an empty slot by 
																			// compairing total no of slots with no of Entered vehicals
			System.out.println("");											// blank Line
			System.out.print("Welcome - To the SLIIT Parking Slot ");		// Printing welcome for the car park
			System.out.println(i+1); 										// Printing the Parking Slot No. By adding one to the 
			i++;															// Incrementing the no of vehicals enterd by one.	
			return true;					
		} else {															// if the condition false
																			// printing cant acsess to the parking at this moment		
			System.out.println("  Parking Full - No Available Space To park Your Vehical.");
			System.out.println("  Please Wait untill a Vehical Leaves");
			System.out.println("  To Remove a Vehical by Open SLIITCarParkManager.java");
		return false;
		}
				
	}

	public int vehicleleft(){					
		return 1;
	}

	public int getNumEmptyslots() {				// This method will print the no. of Empty Slots
		int empty = 0 ;
		empty = totalVehicleSlots - i;
				
		return (empty);
	}

	public int getNumOccupiedslots() {			//// this will print the Occupied Slots
		return (i);	
		}
	}

## Vahical.java

	interface CarParkManager {

	  final int totalVehicleSlots = 20;		//variables to Store total capasity of the Parking
	  boolean vehilceEntered();				// variable to store the no. of vehicals in the park
	  int vehicleleft();					// variable to remove vehicas from the park
	  int getNumEmptyslots();				// variable to get no. of available slots in the park
	  int getNumOccupiedslots();			// variable to store occupied slots.
	
	}

	public abstract class Vehical {		// Abstract VehicalClass

	public String ID_Plate;			// String variable to Store the IDPlate no.
	public String Brand;			// String variable to store vehical Brand
	public String Date;				// String Date
	public int Time;				// string Time
	
	}



## Car.java

	public class Car extends Vehical {

		public int Doors;			// Storing Integer value for no. of Doors
		public String Color;		// Storing String characters for the Color of the car
	
		Car(int Doors, String Color, String ID_Plate, String Brand){
		System.out.println("");
	    	this.ID_Plate = ID_Plate;		
	    	System.out.println("	Car ID_Plate             : " +ID_Plate);	// printing ID_ plate 
	    
		this.Brand = Brand;
    		System.out.println("	Car Brand                : " +Brand);		// printing Car Brand
		
		this.Color = Color;
    		System.out.println("	Colour                   : " +Color);		// Printing the colour
		
		this.Doors = Doors;
    		System.out.println("	No. of Doors             : " +Doors);		// Printing the No. of Doors
		}
	}

## Van.java

	public class Van extends Vehical {
	
		public String type;		// String variable to store the type of the Van
		public int capacity;	// String variable to store the capacity of the van (Goods weight and Seating capacity Both)
	
		Van(String type,int capacity,String ID_Plate,String Brand){		// 
			System.out.println("");
			this.type = type;
			this.Brand = Brand;
			this.ID_Plate = ID_Plate;
		
			System.out.println("	Van ID_Plate             : " +ID_Plate);	// Printing the ID_plate
			System.out.println("	Van Brand                : " +Brand);		// Printing the Brand of the Van
			System.out.println("	Van Type                 : " +type);		// Printing the Type of the Van
	

			if(type == "Passenger") {
				this.capacity = capacity;
				System.out.println("	No.of Seats              : " +capacity+ " Seats only."); 	// Printing the seating capacity 
																									// if the Van is a Passenger Van
				
			}else if(type == "Goods") {
				this.capacity = capacity;
				System.out.println("	Weights carried          : " +capacity+" kg only.");		// Else Print the Goods capasity 
																									// if the Van is Goods Van
			}
		}
	}

## ThreeWheeler.java

	public class ThreeWheeler extends Vehical {
	
		public String purpose;		// String variable to Store The purpose of the ThreeWheeler (Taxi Or NotForHire)
	
		ThreeWheeler(String purpose,String ID_Plate,String Brand){
			System.out.println("");
			this.purpose = purpose;
			this.ID_Plate = ID_Plate;
			this.Brand = Brand;
		
			System.out.println("	Three Wheeler ID_Plate   : " +ID_Plate);	// printing the ID_Plate
			System.out.println("	Three Wheeler Brand      : " +Brand);		// Printing the Brand
	

			if(purpose == "Taxi") {
				System.out.println("	Taxi or NotForHire       : " +purpose);	// Printing the Purpose Taxi
			}
		
			else if(purpose == "NotForHire") {
				System.out.println("	Taxi or NotForHire       : " +purpose);	// Printing the Pupose NotForHire
			}		
		}
	}

## Date_Time.java

	public class Date_Time extends Vehical {
		String date;	// String variable to store Date
		String time;	// String variable to store Time
		Date_Time(String date,String time){
		
			this.date = date;
			this.time = time;
			System.out.println("        Date                     : " +date);			// Printing the date
			System.out.println("        Time                     : " +time+ "Hrs");		// Printing the Time
		}
	}








