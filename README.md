### Hi, I'm Paul 👋

I'm building an **8-bit computer out of 400+ relays**, along with the software to program it: a simulator, an assembler, an IDE and a VS Code language server. The machine is up and running, and it's Turing complete.

[Project blog](https://www.relaycomputer.co.uk/) · [Build videos](https://www.youtube.com/channel/UCDn07eKw2HDPIgSAGQgliAA) · [Featured on Hackaday](https://hackaday.com/2021/01/19/homebrew-relay-computer-looks-like-it-could-be-a-commercial-product/) · [Board designs](https://oshwlab.com/paul_6392)

#### 🔌 The relay computer

| Project                                                                  | What it is                                                                                               | Try it                                              |
| ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| [relay-computer](https://github.com/paul80nd/relay-computer)             | Interactive front panel and animated schematics, in Angular + SVG                                        | [Simulator](https://simulator.relaycomputer.co.uk/) |
| [relay-computer-model](https://github.com/paul80nd/relay-computer-model) | A wire-by-wire simulation of the hardware: cards, backplanes and buses, switching like the real relays   |                                                     |
| [rcasm](https://github.com/paul80nd/rcasm)                               | Assembler for the relay computer's assembly language                                                     |                                                     |
| [relay-computer-ide](https://github.com/paul80nd/relay-computer-ide)     | In-browser editor for writing and assembling programs                                                    | [Editor](https://editor.relaycomputer.co.uk/)       |
| [rcasm-lsp](https://github.com/paul80nd/rcasm-lsp)                       | Language server: diagnostics, hover, completion, go-to-definition and more, in VS Code and in the editor |                                                     |
| [relay-computer-pi](https://github.com/paul80nd/relay-computer-pi)       | Code from the YouTube series on calculating π on the relay computer                                      |                                                     |
| [relay-computer-blog](https://github.com/paul80nd/relay-computer-blog)   | Source for the build blog (Hugo)                                                                         | [Blog](https://www.relaycomputer.co.uk/)            |

#### 📚 Knowledge as Code

**[knowledge-as-code](https://github.com/paul80nd/knowledge-as-code)** keeps engineering knowledge in git, where people and AI coding sessions can both find it. Standards, decisions, runbooks and known fixes each become a typed Markdown **record**, reviewed by pull request like any other change.

- **`kac`**, a .NET command-line tool, checks every record against the schema its type declares, fails CI on a broken cross-reference, and writes the indexes nobody should keep by hand.
- The same records are packaged as a **Claude Code plugin**, so an agent can look up the standard that applies, and cite the rule it followed, before it writes code.
- People read the corpus as a wiki; agents read the plugin built from the same files, so nothing has to be kept true twice.

[Docs](https://paul80nd.github.io/knowledge-as-code/) · [How it compares](https://paul80nd.github.io/knowledge-as-code/compared/) · [NuGet](https://www.nuget.org/packages/KnowledgeAsCode.Tool) · `dotnet tool install --global KnowledgeAsCode.Tool`

#### 🌱 Other projects

- **[forkast](https://github.com/paul80nd/forkast)**: a local-first meal planner ([try it](https://paul80nd.github.io/forkast/))
- **[tilth](https://github.com/paul80nd/tilth)**: a local-first garden almanac & planner ([try it](https://paul80nd.github.io/tilth/))

Both are also experiments in agent-first development: every line is written by Claude via Claude Code, designed through conversation rather than typed by hand.

---

[80nd.co.uk](https://www.80nd.co.uk/) · [relaycomputer.co.uk](https://www.relaycomputer.co.uk/) · [YouTube](https://www.youtube.com/channel/UCDn07eKw2HDPIgSAGQgliAA)
