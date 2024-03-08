<h2>Hey 👋, I'm <a href="www.linkedin.com/in/guilherme-rossi-kirsten">Rossik</a></h2>

<img src="https://media.giphy.com/media/Vuw9m5wXviFIQ/source.gif" width="250" height="auto" alt = 'Awesome Matrix Code' align='right' />


[![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/guilherme-rossi-kirsten-61853a176/)](https://www.linkedin.com/in/haany-ali) [![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:eree0593@gmail.com)](mailto:eree0593@gmail.com) [![Youtube Channel](https://img.shields.io/badge/-Youtube-c14438?style=flat-square&logo=Youtube&link=https://www.youtube.com/@guilhermerossikirsten6778)](https://www.youtube.com/@guilhermerossikirsten6778)
[![Spotify](https://img.shields.io/badge/-@Guilherme%20Rossi%20Kirsten-1ED760?style=flat-square&amp;labelColor=fff&amp;logo=Spotify&amp;link=https://open.spotify.com/user/guirossik-br?si=5cbb52a66b5d429c)](https://open.spotify.com/user/guirossik-br?si=5cbb52a66b5d429c)

**Tools**
<img title="Ubuntu" alt="Ubuntu" width="40px" src="https://raw.githubusercontent.com/github/explore/master/topics/windows/windows.png">|<img title="Linux" alt="Linux" width="40px" src="https://raw.githubusercontent.com/github/explore/master/topics/linux/linux.png">|<img title="ZSH" alt="ZSH" width="40px" src="https://s3.amazonaws.com/ohmyzsh/oh-my-zsh-logo.png">|<img title="VS Code" alt="VS Code" width="40px" src="https://img.icons8.com/fluent/48/000000/visual-studio-code-2019.png">|<img title="git" alt="git" width="40px" src="https://raw.githubusercontent.com/github/explore/master/topics/git/git.png">|<img title="Jupyter Notebook" alt="Jupyter" width="40px" src="https://raw.githubusercontent.com/github/explore/master/topics/jupyter-notebook/jupyter-notebook.png">
|--|--|--|--|--|--|
<br>

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CaioMBA)
![Gitlab](https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white)
![AzureDevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)

## Programming Languages

<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain.svg" alt="bootstrap" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original-wordmark.svg" alt="java" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="mongodb" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="25" height="25" />
<img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original-wordmark.svg" alt="python" width="25" height="25" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="25" height="25" />
<img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="Kubernetes" width="25" height="25" />


</p>

    import java.util.ArrayList;import java.util.List;import java.util.UUID;

    public class WhoAmI {
        private String firstName = "Guilherme";
        private String lastName = "Kirsten";
        private UUID uuid = UUID.randomUUID();
        private String[] hobbies = {
                "Assistir filmes",
                "Jogar online",
                "Viajar",
                "Ficar acordado até achar aquele maldito BUG..."
        };
        List<String> ambitions = new ArrayList<>();

        public WhoAmI() {
            // Adicionando ambições
            ambitions.add("Aprender inglês");
            ambitions.add("Explorar novas tecnologias");
            ambitions.add("Aprender a tocar um instrumento musical");}

        public String getCity() {
            return "São Paulo, Brasil";}

        public void listHobbies() {
            System.out.println("Meus hobbies são:");
            for (String hobby : hobbies) {
                System.out.println("- " + hobby);} }

        public void listAmbitions() {
            System.out.println("Minhas ambições são:");
            for (String ambition : ambitions) {
                System.out.println("- " + ambition); }}

        public static void main(String[] args) {
            WhoAmI person = new WhoAmI();
            System.out.println("Usuário: " + person.firstName + ". " + person.lastName);
            System.out.println("Que a Força esteja com você, " + person.uuid +". Você é único em toda a galáxia.\"");
            System.out.println("Cidade: " + person.getCity());
            System.out.println();
            person.listHobbies();
            System.out.println();
            person.listAmbitions();
        }
    }
