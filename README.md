# RNK Studios

**Universal Minecraft mod compatibility — load any mod on any server.**

RNK Studios builds tooling that lets Minecraft mods run on loaders and platforms they
were never built for: **The Tync**, a Java 21 meta-loader that transforms mods above
Forge, Fabric, Paper, Quilt, Bedrock, and more — and the **Minecraft Bridge**, a Node.js
server companion that detects your server, transforms your mods, and launches.

```
User → Bridge → The Tync engines → transformed mod → server launch
```

## Open source

The framework is open: engine abstraction, engine manager, component loader, trigger
system, delivery pipeline, performance turbos, all 19 loader API libraries, and the
complete Bridge — build your own transformation engine by implementing the `Engine`
interface.

| Repository | What it is |
|---|---|
| [**rnk-public**](https://github.com/RNK-Enterprise/rnk-public) | Open-source distribution — the full framework, CI-verified builds |

The core transformation engines (bytecode metamorphosis, API mapping/bridging, injection,
shim generation, validation, and more) are proprietary and distributed separately.

## Stack

Java 21 · Maven · Project Reactor · Micrometer · Node.js

## Contact

- Issues & support: [rnk-public issues](https://github.com/RNK-Enterprise/rnk-public/issues)
