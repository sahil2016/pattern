public class pattern {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
for(int i=1;i<10;i++)
{
	if(i<=5)
	{
		for(int j=1;j<=i;j++)
		{
			System.out.print(j);
		}
		System.out.println();
	}
		if(i>5)
		{
			
				for(int h=1;h<=(10-i);h++)
				{
					System.out.print(h);
				}
			System.out.println();
		}
}
	}
}


