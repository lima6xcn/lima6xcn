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
        .email = "contact@trenbankai.dev",
        .website = "https://trenbankai.dev/"
    },
    .languages = {"Java", "Kotlin", "C#", "C", "C++", "PHP", "Web Stack"},
    .tech = {"Graphics Programming", "Web", "Android", "Multiplatform", "Minecraft Modidng", "Backend"}
};
```
