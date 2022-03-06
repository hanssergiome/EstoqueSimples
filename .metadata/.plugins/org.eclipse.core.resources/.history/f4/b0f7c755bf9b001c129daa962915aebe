package entities;

public class product {

	public String name;
	public double price;
	public int quantity;
	
	public double totalvalueinstock() {
		
		return price*quantity;
		
	}
	
	public void addproduct (int quantity) {
		
		this.quantity += quantity;
		
	}
	
	public void removeproduct (int quantity) {
		
		this.quantity -= quantity;
		
	}
	
	public String toString() {
		
		return name
				+ ", $ "
				+ price
				+", "
				+quantity
		        + " unidades, total: $"
		        + totalvalueinstock();
		
	}
}
