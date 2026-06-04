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
    // Last update: 04.06.2026 16:03:25 (GMT+2)
    char* activity[] = { 
        "QGPU           |#################=============| 58% (33 commits)",
        "QuneOS         |#####=========================| 17% (10 commits)",
        "QAsm           |####==========================| 16% (9 commits)",
        "QEngine        |##============================|  7% (4 commits)",
        "QCode          |==============================|  0% (0 commits)",
    };
    return 0;
}
