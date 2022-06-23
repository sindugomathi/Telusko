# Telusko
Assignment
/**Created challenge program for telusko community program.
 * I am printing ineuron in this program
 * step 1:Finding out the rows and columns in the letter.
 * step 2:found out the positions were to add "*" and spaces.
 * step 3: looped the number of rows needed.
 * step 4 for loop for each column values and verify the condition in the if loop*/
public class iNeuron {
    public static void main(String[] args){
for(int i=0;i<=5;i++){
        if(i==1){
            for(int k=1;k<35;k++){
                if(k==1||k==2||k==3||k==4||k==5||k==7||k==11||k==13||k==14||k==15||k==17||k==19||k==21||k==22||k==23||k==26||k==27||k==30||k==34)
                    System.out.print("*");
                else if(k==6||k==8||k==9||k==10||k==12||k==16||k==18||k==20||k==24||k==25||k==28||k==29||k==31||k==32||k==33){
                    System.out.print(" ");
            }
        }
        }
        if(i==2){
            System.out.println();
            for(int l=1;l<35;l++){
                if(l==3||l==7||l==8||l==11||l==13||l==17||l==19||l==21||l==23||l==25||l==28||l==30||l==31||l==34)
                    System.out.print("*");
                else if (l==1||l==2||l==4||l==5||l==6||l==9||l==10||l==12||l==14||l==15||l==16||l==18||l==20||l==22||l==24||l==26||l==27||l==29||l==32||l==33)
                    System.out.print(" ");
            }
        }
        if(i==3){
            System.out.println();
            for(int m=1;m<35;m++){
                if(m==3||m==7||m==9||m==11||m==13||m==14||m==17||m==19||m==21||m==22||m==25||m==28||m==30||m==32||m==34)
                    System.out.print("*");
                else if(m==1||m==2||m==4||m==5||m==6||m==8||m==10||m==12||m==15||m==16||m==18||m==20||m==23||m==24||m==26||m==27||m==29||m==31||m==33)
                    System.out.print(" ");
            }
        }
        if(i==4){
            System.out.println();
            for (int n=1;n<35;n++){
                if(n==3||n==7||n==10||n==11||n==13||n==17||n==19||n==21||n==23||n==25||n==28||n==30||n==33||n==34)
                    System.out.print("*");
                if(n==1||n==2||n==4||n==5||n==6||n==8||n==9||n==12||n==14||n==15||n==16||n==18||n==20||n==22||n==24||n==26||n==27||n==29||n==31||n==32)
                    System.out.print(" ");
            }
            }
        if(i==5){
            System.out.println();
            for(int o=1;o<35;o++){
                if(o==1||o==2||o==3||o==4||o==5||o==7||o==11||o==13||o==14||o==15||o==18||o==21||o==23||o==26||o==27||o==30||o==34)
                    System.out.print("*");
                else if(o==6||o==8||o==9||o==10||o==12||o==16||o==17||o==19||o==20||o==22||o==24||o==25||o==28||o==29||o==31||o==32||o==33)
                    System.out.print(" ");
            }
        }

}
    }
}
