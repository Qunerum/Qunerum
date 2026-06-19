```c
#define STATUS "CODING"
typedef struct {
    char* location;       // Country
    char* os;             // Operating System
    char* desktop_env;    // DE
    int experience_yrs;   // Years of coding
} Developer;

int main() {
    Developer me = {
        .location = "Poland 🇵🇱",
        .os = "Arch Linux",
        .desktop_env = "KDE Plasma",
        .experience_yrs = 5
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
        "QGPU - Lightweight 2D Graphics Wrapper & Immediate UI in C built on Vulkan & GLFW",
        "QCode - Programming Language & Interpreter in C",
        "QAsm - Programming Language & Compiler in C targeting x86_64 Assembly",
        "QEngine - A 2D game engine written in C",
    };
    // Last update: 19.06.2026 10:21:27 (GMT+2)
    char* activity[] = { 
        "QGPU           |##############================| 49% (41 commits)",
        "QEngine        |######========================| 20% (17 commits)",
        "QAsm           |#####=========================| 18% (15 commits)",
        "QuneOS         |##============================|  8% (7 commits)",
        "QChat          |==============================|  3% (3 commits)",
    };
    return 0;
}
```
