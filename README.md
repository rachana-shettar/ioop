
import java.io.*;
class Main
{
	public static void main(String arg[])
	{
			int a,b,s;
			DataInputStream dis=new DataInputStream(System.in);
		try
		{
			a=Integer.parseInt(dis.readLine());
			b=Integer.parseInt(dis.readLine());
			s=a+b;
			System.out.println("sum="+s);
		}catch(IOException e)
		{
		}catch(NumberFormatException e)
		{
		}
	}
}
