``` java
public class Mia extends Student {

  // TODO: never stop learning !!

  final String name =            "mia ravishankar";
  final String role =            "cs student @ columbia";
  final String[] sideQuests =    {"photography", "nature", "writing"};
  boolean bobaStatus =           true;

  record Script(String name, String proficiency) {}
  final Script[] stack = new Script[] {
      new Script("java",       "proficient"),
      new Script("python",     "proficient"),
      new Script("c/c++",      "intermediate"),
      new Script("html/css",   "intermediate"),
      new Script("javascript", "intermediate"),
      new Script("sql",        "foundational")
  };

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
