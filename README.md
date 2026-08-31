## Nguyễn Thanh Tuấn

First-year Computer Science student at **PTIT** — Posts and Telecommunications Institute of Technology, Ho Chi Minh City campus, class of D26.

I mostly write **Java** and **Kotlin**. Most of it ends up running on a Minecraft server I host and maintain myself, which turned out to be a good excuse to learn profiling, concurrency and a lot of API archaeology. Heading toward **DevSecOps**.

---

### What I'm working on

**SIVI** — a Paper 26.1.2 server I run end to end, plus the plugins behind it:

- **[sivi-pack-plugin](https://github.com/ObsidianMC123/sivi-pack-plugin)** — pushes 4 resource packs to the client in a *single* request, and keeps the player invulnerable while they download. Turns out calling `sendResourcePacks()` four times wipes the stack each call and only the last pack survives.
- **ZAS** (Kotlin) — zombie-apocalypse spawning and structure generation.
- **CatacraftWeapons** — 21 guns, 2126 animation frames.
- Chased a recurring **620 ms tick spike** down to blocking region-file I/O on the main thread. TPS went from 17.3 to 19.5 after the fix. Wrote an offline `.sparkprofile` parser to get there.

**[AI-Classroom](https://github.com/ObsidianMC123/AI-Classroom)** — ESP32-based smart classroom: environmental monitoring, real-time control over WebSocket, on-device AI.

**WiFi CSI sensing** — channel-state-information sensing, provincial science fair project. Currently being rewritten into something other people can actually run.

---

### Toolbox

`Java` · `Kotlin` · `JavaScript / Node.js` · `PowerShell` · `Gradle` · `Paper API` · `ESP32 / Arduino` · `Git`

---

### A note on this profile

The repos here are a mix of things I built, things I forked to read, and things from before I knew better. **The pinned ones are the ones I'd actually show you.**
