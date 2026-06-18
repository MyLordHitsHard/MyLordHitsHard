<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:21262d&height=120&section=header" width="100%"/>

# Himanshu Dutt
### `Computer Science Engineer · C++ Programmer · Full-Stack Developer`

[![Portfolio](https://img.shields.io/badge/Portfolio-feellord.netlify.app-0d1117?style=for-the-badge&logo=firefox&logoColor=58a6ff&labelColor=161b22)](https://feellord.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0d1117?style=for-the-badge&logo=linkedin&logoColor=58a6ff&labelColor=161b22)](https://www.linkedin.com/in/himanshu--dutt/)
[![GitHub](https://img.shields.io/badge/GitHub-MyLordHitsHard-0d1117?style=for-the-badge&logo=github&logoColor=58a6ff&labelColor=161b22)](https://github.com/MyLordHitsHard)

</div>

---

## `> whoami`

```cpp
class HimanshuDutt {
    std::string role     = "Computer Science Engineer";
    std::string location = "Kishtwar, Jammu & Kashmir, India";
    std::string focus    = "Low-level systems + full-stack web";
    std::string nextGoal = "Game Development";

public:
    auto getPassions()  { return {"C++", "OpenGL", "Spring Boot", "Building things"}; }
    bool isLearning()   { return true; }
    bool drinksCoffee() { return false; /* drinks water lol */ }
};
```

I'm a CS grad who enjoys building things from scratch (sometimes with the help of AI tools :)). Whether it's a full REST API with Google OAuth, a 3D camera system in OpenGL, or a raytracer written in C++. I like understanding how things work at the lowest level and then building something on top of it.

---

## `> skills --list`

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Frameworks & Libraries**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Databases & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Tools & Platforms**

![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=flat-square&logo=visual-studio&logoColor=white)

---

## `> ls projects/`

<details>
<summary><b>🪶 VERSES — Poetry Platform</b></summary>
<br>

A full-stack private poetry publishing platform with a dark, editorial aesthetic.

**What I built:**
- **Backend** — Express.js REST API with `helmet`, `cors`, `express-rate-limit`
- **Auth** — Google OAuth + JWT (7-day tokens, admin-only guard middleware)
- **Database** — PostgreSQL on Neon with cursor-based pagination, GIN indexes for tag search, and a SQL trigger for `updated_at`
- **Like system** — Anonymous toggling via SHA-256 IP hashing (no accounts needed)
- **Frontend** — React with infinite scroll via `IntersectionObserver`, optimistic UI for likes, keyboard shortcuts (`⌘K` search overlay), and a fully hand-rolled CSS design system

**Stack:** `React` `Express.js` `PostgreSQL` `JWT` `Google OAuth` `Neon`

</details>

<details>
<summary><b>🎮 OpenGL 3D Renderer</b></summary>
<br>

A 3D scene renderer built from scratch while learning OpenGL.

**What I implemented:**
- Camera class with Euler angle processing (Yaw, Pitch), keyboard + mouse input, and scroll-based zoom
- Vertex/fragment shader pipeline via a custom `Shader` class (reads GLSL from disk, compiles, links)
- Texture mapping with `stb_image`, blended multi-texture support
- Model → View → Projection matrix pipeline using `glm`
- Depth testing and multiple 3D cube instances at different positions

**Stack:** `C++` `OpenGL 3.3 Core` `GLFW` `GLAD` `glm` `stb_image`

</details>

<details>
<summary><b>🔦 CPU Raytracer</b></summary>
<br>

A software raytracer written in C++ that outputs PPM image files.

**What it does:**
- Ray-sphere intersection with recursive reflections and refractions
- Fresnel effect blending (reflection vs. refraction) using the Schlick approximation
- Hard shadows via secondary shadow rays
- Configurable scene with light-emitting spheres
- Outputs 640×480 PPM renders

**Stack:** `C++` `Math / Linear Algebra` (no external libs)

</details>

<details>
<summary><b>📦 Custom Vector<T> Container</b></summary>
<br>

An STL-compatible generic dynamic array built to understand RAII and move semantics.

**Features:**
- Template class with `emplace_back`, `pop`, bounds-checked `operator[]`
- Amortized O(1) push via capacity doubling
- Move constructor + move assignment (`noexcept`)
- Copy operations explicitly deleted (forces move-only semantics)
- Exception safety on out-of-bounds access

**Stack:** `C++20` `Templates` `Move Semantics` `RAII`

</details>

---

## `> cat stats.json`

<div align="center">

[![GitHub stats](https://github-readme-stats.vercel.app/api?username=MyLordHitsHard&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)](https://github.com/anuraghazra/github-readme-stats)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=MyLordHitsHard&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)](https://github.com/anuraghazra/github-readme-stats)

[![roadmap.sh](https://roadmap.sh/card/tall/6754307decc889bb0d17491f?variant=dark)](https://roadmap.sh)

</div>

---

## `> cat currently.log`

```
[LEARNING]  OpenGL → rendering pipelines, lighting models
[BUILDING]  More side projects, moving toward game dev
[EXPLORING] Low-level systems, graphics programming
[READING]   The Cherno's C++ series + learnopengl.com
```

---

## `> ./contact --help`

| Channel | Link |
|---|---|
| 🌐 Portfolio | [feellord.netlify.app](https://feellord.netlify.app/) |
| 💼 LinkedIn | [himanshu--dutt](https://www.linkedin.com/in/himanshu--dutt/) |
| 🐙 GitHub | [MyLordHitsHard](https://github.com/MyLordHitsHard) |

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=MyLordHitsHard&color=58a6ff&style=flat-square&label=PROFILE+VIEWS)

*"The best way to learn something is to build something with it."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:21262d,50:161b22,100:0d1117&height=80&section=footer" width="100%"/>

</div>
