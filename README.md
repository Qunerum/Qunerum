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
    // Last update: 17.05.2026 10:24:24 (GMT+2)
    char* activity[] = {
        "QCode          |###############===============| 51% (18 commits)"
        "QGPU           |#########=====================| 31% (11 commits)"
        "QuneOS         |###===========================| 11% (4 commits)"
        "Scrap-Display  |#=============================|  5% (2 commits)"
        "QEngine        |==============================|  0% (0 commits)"
    };
    return 0;
}
