# Java
Important Interview Programming Questions and answers (java)
// Input>> bangalore
//Output>> BANGALORE

package org.jsp;
import java.util.Scanner;
public class S25 {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the String--");
		String st = sc.next();
		char[] ch = st.toCharArray();
		for (int i = 0; i < ch.length; i++) {
			if (ch[i] >= 'a' && ch[i] <= 'z')
				ch[i] = (char) (ch[i] - 32);
			else if (ch[i] >= 'A' && ch[i] <= 'Z')
				ch[i] = ch[i];

		}
		for (int i = 0; i < ch.length; i++) {
			System.out.print(ch[i]);
		}

	}
}
