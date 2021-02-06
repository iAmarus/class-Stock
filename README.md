public class Stock {
	//data field
	String symbol;                 
	String name; 
	int ID;
	double previousClosingPrice;	 
	double currentPrice;				
	//constructors
	public Stock(){
		symbol = "";
		name = "";
		ID = 1;
		previousClosingPrice = 1;
		currentPrice = 1;
	}
	public Stock(String newSymbol, String newName , int newID) {
		symbol = newSymbol;
		name = newName;
		newID = ID; 
	}

	// Return the percentage changed from previousClosingPrice to currentPrice
	public double getChangePercent() {
		return ((currentPrice - previousClosingPrice) / 
					previousClosingPrice) * 100;
	}
	public String getName(String name){
		return name = name;
	}
	public String getSymbol(String symbol) {
		return symbol = symbol;
	}
}
