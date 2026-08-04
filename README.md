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
	// Last update: 2026-08-04 19:39 (GMT+2)
	// All commits: 85 (Last 30 days)
	// Q -> Qunerum
	char* activity[] = {
		"QGPU                     |##############================| 48% [  41 commits ]",
		"QCode Plus               |#######=======================| 22% [  19 commits ]",
		"QEngine                  |###===========================| 11% [   9 commits ]",
		"QAsm                     |###===========================|  9% [   8 commits ]",
		"Q Conf Neural Network    |##============================|  5% [   4 commits ]",
	};
	return 0;
}
```
