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
	char* primary_languages[] = {"C", "C#", "QCode", "QCode+", "QAsm"};
	char* secondary_languages[] = {
		"Java", "Python", "Batch", "Assembly",
		"HTML", "CSS", "C++ (Arduino)"
	};
	char* editors[] = {"Kate", "IntelliJ"};
	char* projects[] = {
		"QuneOS - Custom x86/x86_64 OS: Bootloader & Kernel from scratch",
		"QGPU - Lightweight 2D Graphics Wrapper in C built on Vulkan & GLFW",
		"QEngine - 2D game engine written in C",
		"QCode - Programming Language & Interpreter in C",
		"QAsm - Programming Language & Compiler in C targeting x86_64 Assembly",
		"QCode Plus - Programming Language & Compiler in C targeting QAsm",
	};
	// Last update: 20.07.2026 12:28:04 (GMT+2)
	// All commits: 80 (Last 30 days)
	// Q -> Qunerum
	char* activity[] = {
		"QGPU                     |#############=================| 43% (  34 commits )",
		"QCode Plus               |#######=======================| 24% (  19 commits )",
		"QEngine                  |####==========================| 14% (  11 commits )",
		"Q Big Text Generator     |###===========================|  9% (   7 commits )",
		"QAsm                     |###===========================|  9% (   7 commits )",
	};
	return 0;
}
```
