# SME-Factorial

 Task Description:
You have a small Java project with a single class that calculates the factorial of a number. You
are required to:
1) Set up a local SonarQube instance.
2) Use the SonarScanner to analyze the Java project.
3) Identify and describe at least one code smell, bug, or vulnerability reported by SonarQube.
4) Fix the issue and re-run the analysis to confirm the issue is resolved.
Sample Java Code (Before Fix):
public class Factorial {
public static void main(String[] args) {
int result = factorial(5);
System.out.println("Factorial is: " + result);
}
public static int factorial(int n) {
int result = 1;
for (int i = 1; i <= n; i++) {
result *= i;
}
return result;
}
}
Instructions:
• The Deadline for submission is on Saturday May 3th at 11:59 pm.
• The assignment is submitted in groups of 2 students from the same lab or the same TA.
• Please submit one PDF file. The file name should follow this structure:
ID1_ID2_GROUP.pdf 