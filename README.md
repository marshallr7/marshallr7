```java
public class Marshall extends GitHubUser {
  public Marshall() {
    super("marshallr7", "Lubbock, Texas");

    this.addLanguage("Java", "Python", "C", "C++");
    this.addExperience("Keeling Systems LLC", "DawnGames LLC");
  }
}

public abstract class GitHubUser {

  @Getter private final String username;
  @Getter private final String location;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public GitHubUser(String username, String location) {
      this.name = username;
      this.location = location;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=marshallr7&theme=tokyonight)

![](https://visitor-badge.laobi.icu/badge?page_id=marshallr7.marshallr7) [![Github](https://img.shields.io/github/followers/marshallr7?label=Follow&style=social)](https://github.com/marshallr7)
