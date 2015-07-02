# java
sample program for palindrome
class pal
{
	static int num=158945561;
	static String s=String.valueOf(num);
	static char ch[]=new char[s.length()];
	public static void main(String arg[])
	{
		int j=0;
		for(int i=s.length()-1;i>=0;i--)
		{
		ch[j++]=s.charAt(i);
		}
		String rev=String.valueOf(ch);
		if(s.equals(rev))
		{
			System.out.println("the number is a palindrome");
		}
		else
			System.out.println("the number is not  palindrome");
	}
}
