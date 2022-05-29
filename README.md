# kellatirupathi
import java.io.*;
public class Car extends Vehicle {
	private String name;
	private String color;
	public Car(String name,String color)
	{
		super();
		this.name=name;
		this.color=color;
	}
	public String getName()
	{
		return this.name;
	}
	public String getColor()
	{
		return this.color;
	}
}
