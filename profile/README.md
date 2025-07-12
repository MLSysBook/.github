# 📘 Machine Learning Systems: Textbook & Educational Resources

Welcome to the official GitHub organization for the **Machine Learning Systems** textbook.

This open-access, system-first initiative was developed at Harvard University by [Vijay Janapa Reddi](https://profvjreddi.github.io/website/) to train the next generation of AI engineers who think holistically across algorithms, data, hardware, and infrastructure. It reflects a long-term vision to shape the future of machine learning systems education in both academic and applied settings.

---

## 🧰 What You’ll Find

This organization brings the textbook to life with practical, open-source resources for teaching and learning machine learning systems:

- 📘 [**Textbook**](https://mlsysbook.ai): The open-access book that spans the full ML lifecycle, from data to deployment  
- 🔌 [**Hardware Kits**](https://github.com/mlsysbook/kits): Embedded and edge ML projects using TinyML hardware  
- 🧪 [**Labs & Exercises**](https://github.com/mlsysbook/labs): Chapter-aligned exercises and hands-on notebooks  
- 🔧 [**TinyTorch Project**](https://github.com/mlsysbook/tinytorch): Build ML infrastructure from scratch, including autograd, runtime, and training loops  
- 🎓 [**Instructor Courseware**](https://github.com/mlsysbook/courseware): Slides, test banks, and certification resources (in development)  
- 💬 [**Discussions and Forum**](https://github.com/orgs/mlsysbook/discussions): Join the conversation on GitHub discussions and the Discord forum

---

## 👩‍🏫 Who This Is For

- **Students** learning how ML systems are built and deployed  
- **Educators** teaching modern ML from a systems perspective  
- **Engineers** building ML infrastructure in real-world settings  
- **Researchers** exploring hardware-software co-design

---

## 🤔 Frequently Asked Questions

<details>
<summary><strong>Why should students build TinyTorch if AI agents can already generate similar code?</strong></summary>

Even though large language models can generate working ML code, building systems from scratch remains *pedagogically essential*:

- **Understanding vs. Using**: AI-generated code shows what works, but not *why* it works. TinyTorch teaches students to reason through tensor operations, memory flows, and training logic.
- **Systems Literacy**: Debugging and designing real ML pipelines requires understanding abstractions like autograd, data loaders, and parameter updates, not just calling APIs.
- **AI-Augmented Engineers**: The best AI engineers will *collaborate with* AI tools, not rely on them blindly. TinyTorch trains students to read, verify, and modify generated code responsibly.
- **Intentional Design**: Systems thinking can’t be outsourced. TinyTorch helps learners internalize how decisions about data layout, execution, and precision affect performance.

</details>

<details>
<summary><strong>Why not just study the PyTorch or TensorFlow source code instead?</strong></summary>

Industrial frameworks are optimized for scale, not clarity. They contain thousands of lines of code, hardware-specific kernels, and complex abstractions. 

TinyTorch, by contrast, is intentionally **minimal** and **educational** — like building a kernel in an operating systems course. It helps learners understand the essential components and build an end-to-end pipeline from first principles.

</details>

<details>
<summary><strong>Isn't it more efficient to just teach ML theory and use existing frameworks?</strong></summary>

Teaching only the math without implementation leaves students unable to debug or extend real-world systems. TinyTorch bridges that gap by making ML systems tangible:

- Students learn by doing, not just reading.
- Implementing backpropagation or a training loop exposes hidden assumptions and tradeoffs.
- Understanding how layers are built gives deeper insight into model behavior and performance.

</details>

<details>
<summary><strong>Why use TinyML in a Machine Learning Systems course?</strong></summary>

TinyML makes systems concepts concrete. By running ML models on constrained hardware, students encounter the real-world limits of memory, compute, latency, and energy — exactly the challenges modern ML engineers face at scale.

- ⚙️ **Hardware constraints** expose architectural tradeoffs that are hidden in cloud settings.
- 🧠 **Systems thinking** is deepened by understanding how models interact with sensors, microcontrollers, and execution runtimes.
- 🌍 **End-to-end ML** becomes tangible — from data ingestion to inference.

TinyML isn’t about toy problems — it’s about simplifying to the point of *clarity*, not abstraction. Students see the full system pipeline, not just the cloud endpoint.

</details>

<details>
<summary><strong>What do the hardware kits add to the learning experience?</strong></summary>

The hardware kits are where learning becomes **hands-on and embodied**. They bring several pedagogical advantages:

- 🔌 **Physicality**: Students see real data flowing through sensors and watch ML models respond — not just print outputs.
- 🧪 **Experimentation**: Kits enable tinkering with latency, power, and model size in ways that are otherwise abstract.
- 🚀 **Creativity**: Students can build real applications — from gesture detection to keyword spotting — using what they learned in TinyTorch.

The kits act as *debuggable, inspectable deployment targets*. They reveal what’s easy vs. hard in ML deployment — and why hardware-aware design matters.

</details>

---

## 🤝 Contributing

We welcome contributions across all repositories. To get started:

- Review the `README.md` in each individual repository  
- Open an [issue](https://github.com/mlsysbook/labs/issues) to share ideas or suggest improvements  
- Contact us at [contact@mlsysbook.ai](mailto:contact@mlsysbook.ai)

---
📘 https://mlsysbook.ai · 🔬 https://github.com/mlsysbook/labs · 🧰 https://github.com/mlsysbook/kits · 💬 https://github.com/orgs/mlsysbook/discussions
