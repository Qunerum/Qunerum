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
        "QGPU - Lightweight 2D Graphics Wrapper & Immediate UI in C built on Vulkan & GLFW",
        "QCode - Programming Language & Interpreter in C",
        "QAsm - Programming Language & Compiler in C targeting x86_64 Assembly",
        "QEngine - 2D Game Engine: C# version (Abandoned) → Currently being rewritten in C",
    };
    // Last update: 26.05.2026 21:03:43 (GMT+2)
    char* activity[] = { 
        "QCode          |##########====================| 34% (13 commits)",
        "QuneOS         |########======================| 28% (11 commits)",
        "QGPU           |#######=======================| 26% (10 commits)",
        "QAsm           |###===========================| 10% (4 commits)",
        "QEngine        |==============================|  0% (0 commits)",
    return 0;
}
