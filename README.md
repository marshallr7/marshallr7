![](https://visitor-badge.laobi.icu/badge?page_id=marshallr7.marshallr7)

```java
public class Marshall extends GitHubUser {
  public Marshall() {
    super("marshallr7", "Lubbock, Texas");

    this.addLanguage("Java", "Python", "C", "C++");
    this.addExperience("MythicGames LLC", "DawnGames LLC");
  }
}

public abstract class GitHubUser {

  @Getter private final String username;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public GitHubUser(String username, String country) {
      this.name = username;
      this.country = country;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```
