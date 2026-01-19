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



---



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


---


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
 *  Brand:     Oz Studio
 *  Version:   v2.0.25
 *  Status:    ACTIVE 🔥
 */
public class OshadhaProfile extends SoftwareEngineer implements CreativeMind {

    private final String education = "iCET - Diploma in Software Engineering";
    private final String creativeBrand = "Oz Dev Studio;
    private final String[] designSkills = { "Figma", "Photoshop", "Illustrator"};

    private enum Mode {
        DEVELOPMENT, DESIGN, INNOVATION
    }

    private Mode currentMode = Mode.DEVELOPMENT;

    @Override
    public void igniteCreativity() {
        System.out.println("🎨 Creativity Engine Activated → Blending visuals + logic...");
    }

    public void currentFocus() {

        String[] backend = { "Java", "Spring Boot", "MySQL"};
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
        dev.switchMode();
        dev.currentFocus();

        System.out.println("🚀 System Running: Engineering");
    }
}

interface CreativeMind {
    void igniteCreativity();
}
