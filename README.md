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
    char* editors[] = {"IntelliJ", "Rider", "Kate"};
    char* projects[] = {
        "QCode (Programming Language & Compiler in C)",
        "QEngine (Game Engine in C#)",
        "QuneOS (Custom x86/x86_64 OS: Bootloader & Kernel from scratch)",
        "QChest (Modern Crates Plugin for Minecraft)"
    };
    // My current focus & activity level
    // Last update: 26.04.2026 18:47:49 (GMT+2)
    char* activity[] = {
        "QuneOS   |############==================| 43% (22 commits)"
        "QCode    |############==================| 41% (21 commits)"
        "QGPU     |##============================|  7% (4 commits)"
        "QEngine  |#=============================|  5% (3 commits)"
        "QChest   |==============================|  1% (1 commits)"
    };
    return 0;
}
