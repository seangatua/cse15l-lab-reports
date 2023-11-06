**Failure Inducing Input**
@Test
  public void max1() {
    int input1 = 1;
    int input2 = 2;
    lab3.max(1,2);
    assertEquals(input2, lab3.max(input1, input2));
  }

**Resulted Symptom**
![Image](failure.png)
![Image](failure2.png)


**Associated Code**

    public class lab3 {
        static int max(int num1, int num2) {
            if(num1 > num2){
                return num1;
            }
            else if(num2 > num1){
                return -num2;
            }
            else{
               return num1;
           }
         }
    }
**Successful Code**
@Test
    public void max2() {
          int input1 = 2;
          int input2 = 1;
          lab3.max(input1, input2);
      assertEquals(input1, lab3.max(input1, input2));
  }

**Resulted Symptom**
![Image](success.png)

**Associated Code**
public class lab3 {
  static int max(int num1, int num2) {
      if(num1 > num2){
          return num1;
      }
      else if(num2 > num1){
          return -num2;
      }
      else{
          return num1;
      }
    }
}

