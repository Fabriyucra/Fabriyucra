
## Hola, Soy Fabricio 👋

```java
import java.util.Arrays;
import java.util.List;

public class Fabriyucra {

    private String username;
    private String name;    
    private CodeLanguages code;
    private List<String> architecture;

    public Fabriyucra() {
        this.username = "Fabriyucra";
        this.name = "Fabricio Yucra";     
        this.code = new CodeLanguages();
        this.architecture = Arrays.asList("SPA", "MVC", "Serverless", "microservices");
    }

    public String getName() { return name;}

    public CodeLanguages getCode() { return code;}

    public List<String> getArchitecture() { return architecture;}

    @Override
    public String toString() { return name;}

    public static void main(String[] args) {
        Fabriyucra me = new Fabriyucra();
        System.out.println(me);
    }

    public static class CodeLanguages {
        public List<String> frontend = Arrays.asList("HTML", "CSS", "JavaScript", "ReactJS", "Svelte", "Boostrap", "TailWind");
        public List<String> backend = Arrays.asList("Python", "PHP", "Flask", "Django", "Laravel", "NodeJS", "Odoo");
        public List<String> database = Arrays.asList("PostgreSQL", "MySQL", "SQLite3", "Mongo DB");
        public List<String> devops = Arrays.asList("Docker", "Nginx", "Jenkins", "GitHub Actions", "AWS", "Heroku");
        public List<String> tools = Arrays.asList("GIT", "GitHub", "GitLab", "Pandas", "Jupyter notebook", "SQLAlchemy", "Redis", "Celery");
        public List<String> misc = Arrays.asList("Firebase", "TDD", "SCRUM", "SOLID", "GNU/Linux");
    }
}
```
## Get in touch
