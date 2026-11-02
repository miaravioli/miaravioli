``` java
public class Mia extends Student {

  final String name    =  "mia ravishankar";
  final String role    =  "cs student @ columbia";
  boolean bobaStatus   =  true;

  String[] languages   =  {"java", "python", "c/c++", "sql", "javascript", "typescript", "html/css"};
  String[] skills      =  {"pytorch", "opencv", "unity", "react", "MATLAB"};            

  public void welcome() {
    System.out.printf("hey! i'm %s. welcome to my github :)\n", name);
  }

  public String getCurrentFocus() {
    return "locked in college student";
  }

  public boolean isProductive() {
    return bobaStatus;
  }
}

```
