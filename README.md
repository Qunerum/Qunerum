```c
#define STATUS "CODING"
typedef struct {
    char* location;       // Country
    char* os;             // Operating System
    char* desktop_env;    // DE
    float experience_yrs; // Years of coding
} Developer;

int main() {
    Developer me = {
        .location = "Poland 🇵🇱",
        .os = "Arch Linux",
        .desktop_env = "KDE Plasma",
        .experience_yrs = 4.5f
    };
    char* languages[] = {"Polish", "Russian", "English"};
    char* primary_languages[] = {"C", "C#", "QCode"};
    char* secondary_languages[] = {
        "Java", "Python", "Batch", "Assembly",
        "HTML", "CSS", "C++ (Arduino)"
    };
    char* editors[] = {"Kate", "IntelliJ", "Rider"};
    char* projects[] = {
        "QuneOS - Custom x86/x86_64 OS: Bootloader & Kernel from scratch",
        "QGPU - Lightweight 2D Graphics Wrapper & Immediate UI in C built on Vulkan & GLFW"
        "QCode - Programming Language & Compiler in C",
        "QEngine - Custom 2D Game Engine originally in C# (Abandoned in favor of a full C rewrite)",
    };
    // My current focus & activity level
    // Last update: 18.05.2026 21:11:12 (GMT+2)
    char* activity[] = {
        "QCode          |##############================| 48% (16 commits)"
        "QGPU           |#########=====================| 33% (11 commits)"
        "QuneOS         |#####=========================| 18% (6 commits)"
        "QEngine        |==============================|  0% (0 commits)"
    };
    return 0;
}
