# School-quiz-competition
import java.util.Scanner;
public class Main
{
    private static long startTime = System.currentTimeMillis();
	public static void main(String[] args) {
        Scanner s=new Scanner(System.in);
        String str=new String();
        char q1,q2,q3,q4,q5,q6,q7,q8,q9,q10;
        int sum=0;
        System.out.println("WELCOME TO QUIZ");
        System.out.println("instructions :");
        System.out.println("1: quiz will have 10 questions ");
        System.out.println("2: there will be 4 options available for each questions ");
        System.out.println("3: each question has only 1 correct answer ");
        System.out.println("4: for each correct answer you will get 1 point ");
        System.out.println("5: at the end you will get total points you have got ");
        System.out.println("6: you need at least 6 points to pass the quiz and qualify for the next round");
        System.out.println("***all the best*** ");
        System.out.println("ENTER START TO START THE QUIZ");
        str=s.nextLine();
        if(str.length()==5)
        {
        // question no.1
        System.out.println("1: the capital city of united states is ? ");
        System.out.println("(a) Washington,D.C.   (b) Chicago");
        System.out.println("(c) Boston            (d) Atlanta");
        q1=s.next().charAt(0);
        if(q1=='a')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (a) Washington,D.C"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        // question no.2
        System.out.println("2: the speed of light is ? ");
        System.out.println("(a) 5*10^8 m/s        (b) 6*10^8 m/s");
        System.out.println("(c) 3*10^8 m/s        (d) 8*10*8 m/s");
        q2=s.next().charAt(0);
        if(q2=='c')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (c) 3*10^8 m/s"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        // question no.3
        System.out.println("3: the childrens day celebreted on which day ? ");
        System.out.println("(a) 15 November        (b) 16 November");
        System.out.println("(c) 13 November        (d) 14 November");
        q3=s.next().charAt(0);
        if(q3=='d')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (d) 14 November"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        // question no.4
        System.out.println("4: who was the 1st president of india ? ");
        System.out.println("(a) Dr. Zakir Husain              (b) Rajendra Prasad");
        System.out.println("(c) Dr. Sarvepalli Radhakrishnan  (d) Zail Singh");
        q4=s.next().charAt(0);
        if(q4=='b')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (b) Rajendra Prasad"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        // question no.5
        System.out.println("5: the biggest planet of soalr system is ? ");
        System.out.println("(a) Marcury          (b) Earth");
        System.out.println("(c) Saturn           (d) Jupiter");
        q5=s.next().charAt(0);
        if(q5=='d')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (d) Jupiter"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        // question no.6
        System.out.println("6: who was the first man to step on the moon ? ");
        System.out.println("(a) Buzz aldrin             (b) Pete Conrad");
        System.out.println("(c) Neil Armstrong          (d) Alan Bean");
        q6=s.next().charAt(0);
        if(q6=='c')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (c) Neil Armstrong"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        // question no.7
        System.out.println("7: who is the current richest pearson on planet ? ");
        System.out.println("(a) Jeff bezos             (b) Mark Zuckerberg");
        System.out.println("(c) Elon musk              (d) Mukesh ambani ");
        q7=s.next().charAt(0);
        if(q7=='a')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (a) Jeff bezos"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        // question no.8
        System.out.println("8: who is known as iron man of india? ");
        System.out.println("(a) Pandit jawaharlala neharu   (b) Dr.babasaheb ambedkar");
        System.out.println("(c) Saradal patel               (d) APJ abdul kalam ");
        q8=s.next().charAt(0);
        if(q8=='c')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (c) Sardar patel"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        // question no.9
        System.out.println("9: who wrote the constitution of india ? ");
        System.out.println("(a) APJ abdul kalam             (b) Saradal patel");
        System.out.println("(c) Pandit jawaharlala neharu   (d) Dr.babasaheb ambedkar");
        q9=s.next().charAt(0);
        if(q9=='d')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (d) Dr.babasaheb ambedkar"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        // question no.10
        System.out.println("10: the national sport of india is ? ");
        System.out.println("(a) Cricket       (b) Football");
        System.out.println("(c) Hockey        (d) Baseball");
        q10=s.next().charAt(0);
        if(q10=='c')
        {
          System.out.println("CORRECT ANSWER"); 
          sum=sum+1;
        }
        else
        {
           System.out.println("INCORRECT ANSWER"); 
           System.out.println("correct answer is (c) Hockey"); 
        }
        System.out.println("your score " +sum); 
        System.out.print("\n");
        long endTime = System.currentTimeMillis();
        long t= endTime - startTime;
        System.out.println("you took total "+t/1000+" seconds to complete the quiz");
        // result of quizz:
        System.out.println("your final score is " +sum+ " out of 10 ");
        if(sum>=6)
        {
        System.out.println("CONGRATULATION you have PASSED the quiz and qualified for the next round");
        }
        else
        {
        System.out.println("SORRY you have FAILED the quiz and  dosen't qualified for the next round");
        }
         
        }
        else
        System.out.println("INVALID INPUT");
        
        
        

        
	}
}

