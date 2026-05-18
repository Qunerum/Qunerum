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
        "QuneOS - Custom x86/x86_64 OS: Bootloader & Kernel from scratch",
        "QGPU - Lightweight 2D Graphics Wrapper & Immediate UI in C built on Vulkan & GLFW"
        "QCode - Programming Language & Compiler in C",
        "",
    };
    // My current focus & activity level
    // Last update: 18.05.2026 14:58:06 (GMT+2)
    char* activity[] = {
        "QCode          |#############=================| 45% (16 commits)"
        "QGPU           |#########=====================| 31% (11 commits)"
        "QuneOS         |#####=========================| 17% (6 commits)"
        "Scrap-Display  |#=============================|  5% (2 commits)"
        "QEngine        |==============================|  0% (0 commits)"
    };
    return 0;
}
