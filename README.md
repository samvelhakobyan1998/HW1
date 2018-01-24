# HW1

1.import java.util.Scanner;

Public class Age   {

public static void main(String args[])   {
Scanner input = new Scanner(System.in);
int winner = input.nextInt();
int loser = input.nextInt();
last stage = 2 players remain

System.out.printLn ((int)(winner/100 - loser/100) * last stage)

2.import java.util.Scanner;

Public class Age   {

public static void main(String args[])   {
Scanner input = new Scanner(System.in);
int time1 = input.nextInt();
int time2 = input.nextInt();
int time = (time2 / 10000 - time1 / 10000) * 60 + (time2 % 10000 / 100 - time1 % 10000 / 100);
		
if (time2 % 100 < time1 % 100)
time--; //time = time - 1;
		
System.out.println("Complete time: " + time);
	}
}

3.import java.util.Scanner;

public class Palindrome {

	public static void main(String[] args) {
		
		Scanner in = new Scanner(System.in);
		long number = in.nextLong();
		long l2rr = number, rr2l = 0;
	
		while (number > 0) {
			rr2l = rr2l * 10 + number % 10;
			number /= 10;
		}

		System.out.println(l2rr + " is" + (l2rr == rr2l ? "" : " not") + " a palindrome");
	}
	
	
}
