![My languages in repos](https://github.com/Qunerum/QGPG/blob/main/stats.svg)
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
		"HTML", "CSS", "C++ (Arduino)", "JavaScript"
	};
	char* editors[] = {"Kate"};
	char* projects[] = {
		"QuneOS - Custom x86/x86_64 OS: Bootloader & Kernel from scratch",
		"QGPU - Lightweight 2D Graphics Wrapper in C built on Vulkan & GLFW",
		"QEngine - 2D game engine written in C",
		"QCode - Programming Language & Interpreter in C",
		"QAsm - Programming Language & Compiler in C targeting x86_64 Assembly",
		"QCode Plus - Programming Language & Compiler in C targeting QAsm",
	};
	return 0;
}
```
