<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F5AF0,100:2CB67D&height=200&section=header&text=Tom%C3%A1s%20Goicoechea&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Software%20Engineer%20%7C%20Full%20Stack%20%7C%20.NET%20%2B%20AI&descAlignY=56&descSize=18" alt="banner" />
</p>

<!-- Typing -->
<p align="center">
  <a href="https://github.com/tomasgoico7">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=7F5AF0&center=true&vCenter=true&width=650&lines=%C2%A1Hola!+Soy+Tom%C3%A1s+%F0%9F%91%8B;Backend+lover+con+.NET+Core+%26+C%23+%F0%9F%92%9C;Construyendo+soluciones+con+IA+y+LLMs+%F0%9F%A4%96;Colas%2C+cach%C3%A9+y+observabilidad+%E2%9A%99%EF%B8%8F;Problemas+complejos+%E2%86%92+soluciones+simples+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/tomas-goicoechea-0a266a174"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://tomas-goicoechea.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-7F5AF0?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="mailto:tomasgoico7@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=tomasgoico7&style=for-the-badge&color=2CB67D&label=VISITAS" />
</p>

---

## 👨‍💻 Sobre mí

Ingeniero en Informática (UNLaM 🎓) y desarrollador **Full Stack** con ~5 años de experiencia, con el corazón puesto en el **backend**.
Me gusta diseñar APIs prolijas, modelar datos, hacer que las queries vuelen y que los sistemas no se caigan cuando más los necesitás 😅

```csharp
public record Developer
{
    public string Name      => "Tomás Goicoechea";
    public string Location  => "Buenos Aires, Argentina 🇦🇷";
    public string Role      => "Full Stack Developer @ Koovra";
    public string[] Love    => ["Backend", "Arquitectura", "Sistemas distribuidos", "IA aplicada"];
    public string[] Learning => ["AWS Machine Learning", "Go", "Agentic AI"];
    public string Fuel      => "Mate 🧉 + café ☕";
    public string Motto     => "Problemas complejos → soluciones simples";
}
```

- 🔭 En **Koovra** trabajo en **Alfred**, una solución basada en IA que integra LLMs en procesos reales
- ⚙️ Me divierten los **sistemas distribuidos**: colas, caché, rate limiting y observabilidad
- 🤝 Años de trabajo directo con clientes: de relevar el problema a entregar la solución
- 🌱 Siempre aprendiendo algo nuevo (y rompiendo cosas en el camino para entenderlas)

---

## 🛠️ Tech Stack

<p align="center"><b>Backend</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,python,fastapi,go,nodejs,java&theme=dark" />
</p>

<p align="center"><b>Frontend</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=angular,react,nextjs,ts,js,tailwind,bootstrap&theme=dark" />
</p>

<p align="center"><b>Datos · Cloud · DevOps</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,docker,azure,aws,prometheus,grafana,githubactions&theme=dark" />
</p>

<p align="center"><b>IA & herramientas</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/LLMs-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white" />
</p>

---

## 🔥 Proyecto destacado

### 📜 [Papyrus](https://github.com/tomasgoico7/papyrus)
**Sistema distribuido que analiza la compatibilidad entre un CV y una oferta laboral** usando IA.
Tres servicios independientes (Go · Python · Next.js) hablando entre sí como corresponde.

| | |
|---|---|
| 📬 **Cola de trabajos** | Sobre PostgreSQL con `SKIP LOCKED`, reintentos con backoff + jitter y dead letter queue |
| ⚡ **Caché de dos niveles** | LRU en memoria + Redis: un análisis repetido pasó de **~31 s a < 10 ms** |
| 🔭 **Observabilidad** | Correlation IDs, logs estructurados, métricas en Prometheus y tracing con OpenTelemetry |
| 🛡️ **Rate limiting** | Distribuido con Redis + Lua |
| 🤖 **IA** | Score de compatibilidad, skills faltantes y sugerencias generadas vía LLM |

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

---

## 📈 Algunos logros

- 🐛 **~20% menos defectos en producción** aplicando testing automatizado, SOLID y Clean Code
- 🏎️ **Hasta 30% más rápidas** las respuestas optimizando queries y esquemas en SQL Server
- ⏱️ **4-5 horas semanales ahorradas** al equipo automatizando procesos con Python

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=tomasgoico7&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tomasgoico7&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=tomasgoico7&theme=tokyonight&hide_border=true" />
</p>

---

## 🌎 Idiomas

🇦🇷 Español (nativo) · 🇬🇧 Inglés · 🇧🇷 Portugués (básico)

---

<p align="center">
  <b>💬 ¿Charlamos de .NET, IA o arquitectura? ¡Escribime!</b><br/>
  <i>Siempre hay mate 🧉 virtual para una buena conversación</i>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2CB67D,100:7F5AF0&height=120&section=footer" width="100%" />
