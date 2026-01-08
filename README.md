<div align="center">

<!-- Animated Title -->
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=32&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=800&lines=Oshadha+Palliyaguru;Trainee+Software+Engineer;Creative+Technologist+%7C+3D+Developer;Java+%7C+Spring+Boot+%7C+React+%7C+Three.js;Cinematic+Tech+Storyteller" />

<br/>

<!-- 3D Gradient Banner -->
<img src="https://capsule-render.vercel.app/api?type=rect&height=120&text=Oshadha%20Palliyaguru&fontAlign=50&fontAlignY=55&fontColor=00eaff&color=000000&fontSize=45&desc=Trainee%20Software%20Engineer%20%7C%20Creative%20Tech%20Developer&descAlignY=80&descSize=14" />





</div>

---

## ⚡ Tech Stack 
<div align="center">
<img src="https://skillicons.dev/icons?i=java,spring,maven,gradle,mysql,hibernate,redis,postman,docker&perline=10" />
<br/>
<img src="https://skillicons.dev/icons?i=react,js,ts,threejs,html,css,tailwind,bootstrap,vite&perline=10" />
<br/>
<img src="https://skillicons.dev/icons?i=git,github,vscode,idea,figma,ps,ai,pr,ae&perline=10" />
</div>

---

## 🏆 GitHub Trophies
<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=OshadhaPalliyaguru&theme=radical&no-frame=true&row=1&column=7" />
</div>

---

## ⭐ GitHub Stats
<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=OshadhaPalliyaguru&show_icons=true&theme=tokyonight&hide_border=true" />
</div>

---

## 🔥 GitHub Streak  
<div align="center">
<img src="https://streak-stats.demolab.com?user=OshadhaPalliyaguru&theme=tokyonight&hide_border=true" />
</div>

---

## 🔧 Top Languages  
<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=OshadhaPalliyaguru&layout=compact&theme=tokyonight&hide_border=true&langs_count=10" />
</div>

---

## 🐍 Contribution Snake  
<div align="center">
<img src="https://github.com/OshadhaPalliyaguru/OshadhaPalliyaguru/blob/output/github-contribution-grid-snake.svg" />
</div>

---

## 📈 Activity Graph  
<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=OshadhaPalliyaguru&theme=react-dark&hide_border=true&area=true" />
</div>

---

## 🧩 Badges
<div align="center">
<img src="https://komarev.com/ghpvc/?username=OshadhaPalliyaguru&color=blueviolet&style=flat-square" />
<img src="https://img.shields.io/github/followers/OshadhaPalliyaguru?style=social" />
<img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" />
</div>

---

## 🔗 Connect With Me
<div align="center">
  <a href="[https://linkedin.com/in/YOUR_LINKEDIN_URL](https://www.linkedin.com/in/oshadha-palliyaguru/)"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:moshadha23@gmail.com"><img src="https://img.shields.io/badge/Email-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" />
</div>

---

# 🧠 About Me (System Boot Sequence)

```java
/**
 * ================================================
 *    OSHADHA PALLIYAGURU - SYSTEM BOOT SEQUENCE
 * ================================================
 *  Role:      Trainee Software Engineer
 *  Brand:     OzBeatz SL | Cinematic Visuals
 *  Version:   v2.0.25
 *  Status:    ACTIVE 🔥
 */
public class OshadhaProfile extends SoftwareEngineer implements CreativeMind {

    private final String education = "iCET - Diploma in Software Engineering";
    private final String creativeBrand = "OzBeatz SL | Cinematic Visuals";
    private final String[] designSkills = { "Figma", "Photoshop", "Illustrator", "Filmora" };

    private enum Mode {
        DEVELOPMENT, DESIGN, INNOVATION, CINEMATIC_MODE
    }

    private Mode currentMode = Mode.DEVELOPMENT;

    @Override
    public void igniteCreativity() {
        System.out.println("🎨 Creativity Engine Activated → Blending visuals + logic...");
    }

    public void currentFocus() {

        String[] backend = { "Java", "Spring Boot", "MySQL", "WebSockets" };
        String[] frontend = { "React", "Three.js", "TailwindCSS" };
        String[] mission = {
            "Build scalable systems",
            "Craft smooth user experiences",
            "Design cinematic tech stories",
            "Push limits with creative engineering"
        };

        System.out.println("\n--- Live System Log ---");
        System.out.println("Backend Stack Loaded: " + Arrays.toString(backend));
        System.out.println("Frontend Stack Loaded: " + Arrays.toString(frontend));
        System.out.println("Mission Protocol: " + Arrays.toString(mission));
        System.out.println("Operating Mode: " + currentMode);
        System.out.println("------------------------\n");
    }

    public void switchMode(Mode mode) {
        this.currentMode = mode;
        System.out.println("⚡ Mode Switched → " + mode);
    }

    public static void main(String[] args) {

        OshadhaProfile dev = new OshadhaProfile();

        dev.igniteCreativity();
        dev.switchMode(Mode.CINEMATIC_MODE);
        dev.currentFocus();

        System.out.println("🚀 System Running: Engineering x Art Fusion Active.");
    }
}

interface CreativeMind {
    void igniteCreativity();
}
