# SoftwareProject
import java.util.Scanner;
public class YunSuan {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		System.out.println("1.真分数运算 2.整数运算");
		Scanner s=new Scanner(System.in);
		System.out.println("please choose one mode");
		int k = s.nextInt();
		
		//zhenfenshu
		if(k==1)
		{
			for(int i=0;i<30;i++)
			{
				// first number
				int m = (int)(Math.random()*100);
				int n = (int)(Math.random()*100);
				// second number
				int a = (int)(Math.random()*100);
				int b = (int)(Math.random()*100);
			
				int f = (int)(Math.random()*100);
				//cut
				if(f%4==0) 
				{
					if(n==0||b==0) 
					{
						int t1=0;
						while(t1==0)
						{
							n = (int)(Math.random()*100);
							b = (int)(Math.random()*100);
							if(n!=0&&b!=0)
								t1=1;
						}
						if(m>=n||a>=b)
						{
							int t2=0;
							while(t2==0)
							{
								m = (int)(Math.random()*100);
								n = (int)(Math.random()*100);
								a = (int)(Math.random()*100);
								b = (int)(Math.random()*100);
								if(m<n&&a<b)
									t2=1;
							}
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" - "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" - "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" - "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" - "+a+"/"+b+" = ");
						}
						else 
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" - "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" - "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" - "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" - "+a+"/"+b+" = ");
					}
					else
					{
						if(m>=n||a>=b)
						{
							int t3=0;
							while(t3==0)
							{
								m = (int)(Math.random()*100);
								n = (int)(Math.random()*100);
								a = (int)(Math.random()*100);
								b = (int)(Math.random()*100);
								if(m<n&&a<b)
									t3=1;
							}
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" - "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" - "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" - "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" - "+a+"/"+b+" = ");
						}
						else 
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" - "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" - "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" - "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" - "+a+"/"+b+" = ");
					}
				}
				
				//add
				else if(f%4==1)
					if(n==0||b==0) 
					{
						int t4=0;
						while(t4==0)
						{
							n = (int)(Math.random()*100);
							b = (int)(Math.random()*100);
							if(n!=0&&b!=0)
								t4=1;
						}
						if(m>=n||a>=b)
						{
							int t5=0;
							while(t5==0)
							{
								m = (int)(Math.random()*100);
								n = (int)(Math.random()*100);
								a = (int)(Math.random()*100);
								b = (int)(Math.random()*100);
								if(m<n&&a<b)
									t5=1;
							}
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" + "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" + "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" + "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" + "+a+"/"+b+" = ");
						}
						else 
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" + "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" + "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" + "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" + "+a+"/"+b+" = ");
					}
					else
					{
						if(m>=n||a>=b)
						{
							int t6=0;
							while(t6==0)
							{
								m = (int)(Math.random()*100);
								n = (int)(Math.random()*100);
								a = (int)(Math.random()*100);
								b = (int)(Math.random()*100);
								if(m<n&&a<b)
									t6=1;
							}
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" + "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" + "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" + "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" + "+a+"/"+b+" = ");
						}
						else 
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" + "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" + "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" + "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" + "+a+"/"+b+" = ");
					}
				
				//multiply 
				else if(f%4==2)
					if(n==0||b==0) 
					{
						int t7=0;
						while(t7==0)
						{
							n = (int)(Math.random()*100);
							b = (int)(Math.random()*100);
							if(n!=0&&b!=0)
								t7=1;
						}
						if(m>=n||a>=b)
						{
							int t8=0;
							while(t8==0)
							{
								m = (int)(Math.random()*100);
								n = (int)(Math.random()*100);
								a = (int)(Math.random()*100);
								b = (int)(Math.random()*100);
								if(m<n&&a<b)
									t8=1;
							}
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" * "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" * "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" * "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" * "+a+"/"+b+" = ");
						}
						else 
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" * "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" * "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" * "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" * "+a+"/"+b+" = ");
					}
					else
					{
						if(m>=n||a>=b)
						{
							int t6=0;
							while(t6==0)
							{
								m = (int)(Math.random()*100);
								n = (int)(Math.random()*100);
								a = (int)(Math.random()*100);
								b = (int)(Math.random()*100);
								if(m<n&&a<b)
									t6=1;
							}
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" * "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" * "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" * "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" * "+a+"/"+b+" = ");
						}
						else 
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" * "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" * "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" * "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" * "+a+"/"+b+" = ");
					}
				
				//divide
				else if(f%4==3)
					if(n==0||b==0) 
					{
						int t9=0;
						while(t9==0)
						{
							n = (int)(Math.random()*100);
							b = (int)(Math.random()*100);
							if(n!=0&&b!=0)
								t9=1;
						}
						if(m>=n||a>=b)
						{
							int t0=0;
							while(t0==0)
							{
								m = (int)(Math.random()*100);
								n = (int)(Math.random()*100);
								a = (int)(Math.random()*100);
								b = (int)(Math.random()*100);
								if(m<n&&a<b)
									t0=1;
							}
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" / "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" / "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" / "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" / "+a+"/"+b+" = ");
						}
						else 
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" / "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" / "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" / "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" / "+a+"/"+b+" = ");
					}
					else
					{
						if(m>=n||a>=b)
						{
							int t11=0;
							while(t11==0)
							{
								m = (int)(Math.random()*100);
								n = (int)(Math.random()*100);
								a = (int)(Math.random()*100);
								b = (int)(Math.random()*100);
								if(m<n&&a<b)
									t11=1;
							}
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" / "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" / "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" / "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" / "+a+"/"+b+" = ");
						}
						else 
							//若分子为0 直接输出0
							if(m==0&&a==0)
								System.out.println("0"+" / "+"0"+" = ");
							else if(m==0&&a!=0)
								System.out.println("0"+" / "+a+"/"+b+" = ");
							else if(m!=0&&a==0)
								System.out.println(m+"/"+n+" / "+"0"+" = ");
							else if(m!=0&&a!=0)
								System.out.println(m+"/"+n+" / "+a+"/"+b+" = ");
					}
			}
		}
		
		//zhengshu
		else 
		if(k==2)
		{
			for(int j=0;j<30;j++)
			{
				int x = (int)(Math.random()*100);
				int y = (int)(Math.random()*100);
				int z = (int)(Math.random()*100);
				if(z%4==0) 
					System.out.println(x+"-"+y+"=");
				else if(z%4==1)
					System.out.println(x+"+"+y+"=");
				else if(z%4==2)
					System.out.println(x+"*"+y+"=");
				else if(z%4==3)
					//判断除数为0的情况
					if(y==0)
					{
						int p=0;
						while(p==0)
						{
							 y = (int)(Math.random()*100);
							 if(y!=0)
								 p=1;
						}
						System.out.println(x+"/"+y+"=");
					}
					else if(y!=0)
						System.out.println(x+"/"+y+"=");
					
			}
		}
		
	}

}
