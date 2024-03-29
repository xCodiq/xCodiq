<a href="https://twitter.com/xCodiq/" target="blank"><img src="https://img.shields.io/twitter/follow/xcodiq?logo=twitter&style=for-the-badge" alt="xcodiq" /></a>

```java
public class Cody extends GitHubUser {

  public Cody() {
    super("xCodiq", "The Netherlands");

    this.addLanguage("Java", "C++", "C", "Python", "C#");
    this.addExperience(
      "MineTrade",
      "Respawn",
      "MineSuperior",
      "Blocky, LLC", 
      "MelonSMP", 
      "Antarctica Studios", 
      "The Minecart", 
      "Godwars", 
      "Chasecraft LLC"
    );
  }
}

public abstract class GitHubUser {

  @Getter private final String username;
  @Getter private final String country;

  private final Set<String> languages = new HashSet<>();
  private final Set<String> experiences = new HashSet<>();

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
![xCodiq's github stats](https://github-readme-stats.vercel.app/api?username=xCodiq&count_private=true&show_icons=true&theme=dark&hide_border=false) ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=xCodiq&theme=dark&count_private=true)

