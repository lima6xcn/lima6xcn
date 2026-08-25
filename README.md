```c
typedef struct {
    const char* name;
    const char* email;
    const char* website;
} About;

typedef struct {
    About about;
    const char* languages[2];
    const char* tech[8];
} Developer;

Developer developer = {
    .about = {
        .name = "Gabriel",
        .email = "gabriel@firewavestudios.com",
        .website = "https://trenbankai.com/"
    },
    .languages = {"Java", "Kotlin", "C#", "C", "C++", "PHP", "TS/JS", "HTML/CSS"},
    .tech = {"Godot", "Raylib", "SDL", "OpenGL", "D3D11", "Vulkan", "Minecraft Modidng", "Backend"}
};
```
