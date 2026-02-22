# 👋 Hi, I'm Elliot

```go
package main

import "github.com/elliot727/gocvkit"

func main() {
    dev := Developer{
        Name:     "Elliot Silver",
        Focus:    []string{"Systems Programming", "Computer Vision", "iOS Architecture"},
        Creator:  "GoCVKit", // Production-ready OpenCV framework for Go
        Philosophy: "Stability > Hype",
    }
    
    dev.Build()
}
```

---

## 🚀 What I Build

I create tools that bridge the gap between complex systems programming and intuitive user experiences.

### **GoCVKit** (Featured Project)
The OpenCV framework Go was waiting for. I built this because existing solutions were either too low-level (manual memory management) or too unstable for production.
- **What it does:** Declarative, hot-reloadable computer vision pipelines.
- **Key Engineering:** Pre-allocated double-buffering, strict resource lifecycle (`Validate`/`Close`), and crash-safe error handling.
- **Status:** **v2.0.0** – Stable, tested, and ready for production.
- 🔗 **[View GoCVKit Repository](https://github.com/Elliot727/gocvkit)**

### **iOS & SwiftUI**
Leveraging years of mobile development to build performant, accessible apps with clean architecture.
- Focus on reactive patterns (Combine/SwiftUI) and type-safe design.
- Bridging native performance with modern declarative UI.

---

## 🛠 Technical Stack

| Domain | Technologies |
| :--- | :--- |
| **Systems & Backend** | **Go**, Python, TOML |
| **Mobile & Frontend** | Swift, SwiftUI, Combine, TypeScript, React |
| **Computer Vision** | OpenCV, GoCV, Image Processing Algorithms |
| **Design & Tools** | Figma, Xcode, Git, CI/CD Pipelines |

---

## 💡 Engineering Philosophy

- **Honesty over Hype:** I don't claim "zero allocations" if the GC exists. I claim "deterministic performance" and back it up with profilers.
- **Safety First:** If a config is invalid, the app should tell you, not segfault. Resource leaks are bugs, not features.
- **Developer Experience:** Complex tools should have simple APIs. If it requires boilerplate, the abstraction is leaking.

---

## 📈 Current Focus

- **High-Performance Go:** Optimizing cgo boundaries and minimizing GC pressure in real-time video streams.
- **Cross-Platform CV:** Exploring ways to share computer vision logic between Go backends and Swift frontends.
- **Robust Architecture:** Designing systems that degrade gracefully under load rather than crashing.

---

## 🤝 Connect

I'm open to discussing systems architecture, computer vision challenges, or iOS engineering.

- **X (Twitter):** [@codewithelliot](https://x.com/CodeWithElliot)

---

> *"Code is like humor. When you have to explain it, it's bad."* – Cory House

📜 **License:** MIT © 2025 Elliot Silver
