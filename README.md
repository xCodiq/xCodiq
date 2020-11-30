<a href="https://twitter.com/xCodiq/" target="blank"><img src="https://img.shields.io/twitter/follow/xcodiq?logo=twitter&style=for-the-badge" alt="xcodiq" /></a> <a href="https://twitter.com/playnepvp/" target="blank"><img src="https://img.shields.io/twitter/follow/playnepvp?logo=twitter&style=for-the-badge" alt="playnepvp" /></a>

```java
public class xCodiq extends GitHubUser {

  public xCodiq() {
    super("xCodiq", "The Netherlands");

    this.addLanguage("Java", "Python", "Javascript");
  }
}

public abstract class GitHubUser {

  @Getter private final String name;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();

  public GitHubUser(String name, String country) {
      this.name = name;
      this.country = country;
  }

  public void addLanguage(String... language) {
    languages.addAll(language);
  }
}
```
![Codiq's github stats](https://github-readme-stats.vercel.app/api?username=xCodiq&count_private=true&show_icons=true&theme=dark&hide_border=false) ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=xCodiq&theme=dark&count_private=true)

