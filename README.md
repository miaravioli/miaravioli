``` java
public class Mia extends Student {

  // TODO: never stop learning !!

  final String name         =  "mia ravishankar";
  final String role         =  "cs student @ columbia";
  boolean bobaStatus        =  true;

  String[] languages        =  {"java", "python", "c/c++", "sql", "javascript", "typescript", "html/css"};
  String[] skills           =  {"flask", "SQLAlchemy", "aws", "kubernetes", "ci/cd"};            

  public void welcome() {
    System.out.printf("hey! i'm %s. welcome to my happy place :)\n", name);
  }

  public String getCurrentFocus() {
    return "learn & build fun projects";
  }

  public boolean isProductive() {
    return bobaStatus;
  }
}

```
