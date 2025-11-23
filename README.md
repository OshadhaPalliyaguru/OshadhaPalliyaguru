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
