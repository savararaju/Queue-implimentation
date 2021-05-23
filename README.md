# Queue-implimentation


public class Queue
 {
    public int arr[];
    int top;
    int rear;
     Queue()
    {
        top=0;
        rear=-1;
        arr=new int[100];
    }
  public boolean isempty()
  {
      return top>rear;
  }
    public void insert(int v)
    {
        arr[++rear]=v;
    }
    public int remove()
    {
        return arr[top++];
    }
    



    public static void main(String[] args)
    {
        Queue ob=new Queue();
           int data=1;
            
       ob.insert(data);
        //ob.insert(data:2);
         //ob.insert(data:3);
    
 System.out.println(ob.remove());
 //System.out.println(ob.remove());
 //System.out.println(ob.remove());
 System.out.println(ob.isempty());
 
    }
    
}   

