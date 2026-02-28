### <h1> Ciao a tutti 👋 sono Francesco Gentile </h1>
### Languages and tools:
[![My Skills](https://skillicons.dev/icons?i=java,js,html,css,tailwind,react,nodejs,express,mongodb,mysql,postman,git,docker,kubernetes,nginx,rabbitmq,kafka,figma,insomnia&theme=light)](https://skillicons.dev)

# Entusiasta all'opera! - Francesco IM Gentile's Portfolio 💼👨‍💻 👋

Sono un appassionato **Junior Full-Stack Developer** e sono qui per condividere la mia passione per la programmazione e le soluzioni creative con il mondo.

## 🛠️ Competenze Tecniche

## 🛠️ Competenze Tecniche

| Front-End | Back-End / Java Ecosystem | Databases & Storage | DevOps & Infrastructure | Tools & Methodologies |
|-----------|--------------------------|-------------------|------------------------|--------------------|
| - HTML5 🌐<br>- CSS3 🎨<br>- TailwindCSS 🌟<br>- SCSS ⚛️<br>- Bootstrap ⚛️<br>- ReactJS ⚛️<br>- Angular ⚛️<br>- TypeScript ⚛️ | - Java 21 ☕<br>- Spring Boot 3.x 🚀<br>- Spring Data JPA + Hibernate 🗄️<br>- Node.js 🚀<br>- Express 🛤️ | - MySQL 🐬<br>- MongoDB 📊<br>- Redis 🔑<br>- Elasticsearch 🔍<br>- S3 / MinIO 🗂️ | - Docker 🐳<br>- Kubernetes ☸️<br>- Nginx / Traefik 🌐<br>- RabbitMQ / Kafka ⚡<br>- Flyway / Liquibase 📜 | - Git 📜<br>- GitHub 🐱<br>- Insomnia 💤<br>- Postman 📮<br>- Agile 🏁<br>- Scrum 🔄 |

## 🚀 Key Attributes

Sono conosciuto per essere:

- **Creativo:** Amo risolvere problemi complessi con soluzioni innovative. 🎨  
- **Ambizioso:** Sono sempre alla ricerca di nuove sfide e opportunità di apprendimento. 🚀  
- **Appassionato:** La mia passione per la tecnologia guida il mio lavoro quotidiano. 🔥  
- **Capace:** Mi impegno a fornire codice di alta qualità e soluzioni efficaci. 💡  
- **Determinato:** Non mi tiro indietro di fronte alle sfide e lavoro sodo per raggiungere i miei obiettivi. 💪  
- **Equilibrato:** Mantengo un equilibrio tra lavoro e vita privata per massimizzare la mia produttività. ⚖️  
- **Gentile:** Sono un team player e collaboro bene con gli altri. 🤝  
- **Puntuale:** Rispetto sempre le scadenze dei progetti. 🕒  
- **Intrepido:** Non ho paura di affrontare nuove tecnologie o compiti impegnativi. 😎  
- **Ingegnoso:** Trovo soluzioni creative anche ai problemi più difficili. 🤓


Non vedo l’ora di collaborare con te su progetti entusiasmanti! 
Che tu sia un professionista HR o un altro sviluppatore, sentiti libero di contattarmi 
per opportunità di lavoro o per condividere idee e suggerimenti.

public class DeveloperProfile {

    private String name;
    private int enthusiasmLevel;   // 0-10
    private int creativityLevel;   // 0-10
    private int determinationLevel; // 0-10
    private String language;       // "EN" o "IT"

    public DeveloperProfile(String name, int enthusiasm, int creativity, int determination, String language) {
        this.name = name;
        this.enthusiasmLevel = enthusiasm;
        this.creativityLevel = creativity;
        this.determinationLevel = determination;
        this.language = language;
    }

    public void startCoding() {
        if (language.equalsIgnoreCase("IT")) {
            System.out.println("Ciao! Sono " + name + " e inizio a programmare con " 
                + enthusiasmLevel + " entusiasmo, " 
                + creativityLevel + " creatività e " 
                + determinationLevel + " determinazione! 💻");
        } else {
            System.out.println("Hi! I'm " + name + " and let's start coding with " 
                + enthusiasmLevel + " enthusiasm, " 
                + creativityLevel + " creativity, and " 
                + determinationLevel + " determination! 💻");
        }

        // Mostra un piccolo elenco di skill principali
        System.out.println("⚙️ Skills principali: Java ☕ | Spring Boot 🚀 | MySQL 🐬 | Docker 🐳 | Git 📜");
    }

    public static void main(String[] args) {
        DeveloperProfile profile = new DeveloperProfile("Francesco Gentile", 7, 8, 9, "IT");
        profile.startCoding();
    }
}
