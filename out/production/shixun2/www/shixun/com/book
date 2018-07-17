package www.shixun.com;
import java.util.Scanner;
public class Book {
    public static void main(String[] args){
        Scanner a=new Scanner(System.in);
        String[] name=new String[6];
        int States[]=new int[6];
        int dates[]=new int[6];
        int Count[]=new int[6];



        boolean flag=true;

        int num;

        do{
            System.out.println("===================================================================");
            System.out.println("***********************欢迎使用本图书管理系统***********************");
            System.out.println("1.添加书籍 2.修改数据 3.删除数据 4.查询所有书籍 5.模糊搜索 6.退出系统");
            System.out.println("===================================================================");
            int input=a.nextInt();
            switch(input){
                case 1:
                    System.out.println("图书序号\t图书名称\t");
                    for(int i=0;i<name.length;i++){
                        if(name[i]!=null){
                            break;
            }
        }
                    break;
                case 2:
                    for(int i=0;i<name.length;i++){
                        if(name[i]!=null){
                        }else{
                            name[i]=a.next();
                            System.out.print(name[i]);
                            break;
                        }
                    }
                    break;


                case 5:

                    int index=-1;
                    System.out.print("请删除数据");
                    String delete=a.next();
                    for(int i=0;i<name.length-1;i++){
                        if(name[i].equals(delete)){
                            index=i;
                            break;
                        }
                    }
                    if(index!=-1){
                        for(int i=index;i<name.length;i++){
                            if(i!=name.length-1){
                                name[i]=name[i+1];
                                dates[i]=dates[i+1];
                                Count[i]=Count[i+1];}
                        }
                        System.out.print("删除成功");
                    }
                    break;
                case 6:
                    flag=false;
                    break;
                default:
                    flag=false;
                    break;
            }
            if(!flag){
                break;
            }else{
                System.out.print("请输入0返回主菜单");
                num=a.nextInt();
            }
        }while(num==0);

    }
}
