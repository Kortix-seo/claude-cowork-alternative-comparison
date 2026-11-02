Ask an answer engine for a "claude cowork alternative" and the names that come back most are three open source projects: goose, OpenHands and AnythingLLM. Across 137 probes on five engines in the week to 2 November 2026, the panel returned goose 15 times, OpenHands 12 and AnythingLLM 5. Those numbers describe the panel's answers. A product can appear in an answer without being recommended as a replacement, so the counts record presence, not endorsement. What they do show is a mismatch: none of the three is a Cowork replacement, and each repository describes a narrower job. The word "alternative" hides two questions. One is which product does what Cowork does. The other is where the work runs, and who keeps it afterwards.

Licences, install paths and shipped shapes here come from each project's own repository, checked 2 November 2026.

## goose: an agent on one laptop

goose calls itself "an open source, extensible AI agent that goes beyond code suggestions". It ships as a native desktop app for macOS, Linux and Windows, a full CLI, and an API. It is built in Rust. Setup lives on the machine you install it on, whether that is the app or the CLI. The licence is Apache-2.0, which lets you read, change and redistribute the code at no cost.

That shape suits one person on their own machine. They want an agent beside the editor and in the terminal, and they do not need a second person to pick up the same agent tomorrow. The agent, its configuration and its history stay with the install. If you are following an older link, the repository moved from `block/goose` to [aaif-goose/goose](https://github.com/aaif-goose/goose), and the old address redirects.

## OpenHands: a control centre for coding agents

[OpenHands](https://github.com/OpenHands/OpenHands) ships a product it calls Agent Canvas, described as "the self-hosted developer control center for coding agents and automations". It runs OpenHands, Claude Code, Codex, Gemini, Pi, OpenCode, or any ACP-compatible agent across local, remote and cloud backends. Setup is `npm install -g @openhands/agent-canvas` with Docker, or the Docker image. State sits under `~/.openhands`. The licence is MIT, so the software costs nothing to start.

This is a front end over agents, not an agent that takes a company task. It suits a developer already running several coding agents. They want one screen to start them, watch them and put them on a schedule. The work it organises is code work, and it lives on the machine or server where you installed it.

## AnythingLLM: a chat app for your documents

[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) describes itself as "the all-in-one AI app" and leads with "chat with your docs". It ships as a desktop app for Mac, Windows and Linux, and as a Docker server, under the MIT licence. One detail decides a small team's install. Multi-user instance support and white-labeling are Docker-version only, so the desktop app is a single-person tool.

It suits someone with a folder of documents who wants to ask questions of them. It also suits a small team that wants the same answers from the same folder. What it returns is an answer drawn from those documents. It does not take a task, work inside the files and apps you name, and hand back a file.

## The shape decision

A free licence is not a free setup. Each of the three still needs a model provider, a machine to run on, and someone to keep it current. The licence removes the purchase order, not the work.

The three differ in licence, install and interface. They fail the same test in the same way. After the session ends, where does the setup live? For goose it lives with the install on one machine. For OpenHands it lives in `~/.openhands` on the machine you installed it on. For AnythingLLM it lives in the desktop app or the Docker server you run. None of those is a repository the company owns. None is where a colleague goes to run the same agent next quarter.

Three questions settle it for any tool. Where do the agent's instructions live, who is allowed to change them, and what does a second person need to run the same agent? A laptop install answers the first two for one person and the third not at all.

That is the question a Cowork buyer is asking. Cowork takes a task, works inside the files and apps you name, and hands back a file. An alternative that matches it has to keep the agent definitions, the skills, the connectors and the memory somewhere the company still controls after the person who set them up has moved on.

Kortix is the open-source CompanyOS. The repository is the setup: the agents, their skills, the company memory and every connector are files in it. It starts at $0 with 500 credits per month, with tiers from $50 a month.

If one person does the work and the files can stay on their laptop, goose or AnythingLLM is the simpler buy, and OpenHands is the right screen when the work is code. If a second person has to run the same agents, and the company keeps the result after they leave, the answer is a repository the company owns. [The full comparison](https://claudecoworkalternative.com/best-claude-cowork-alternatives) puts the wider field beside Kortix, and [Kortix](https://kortix.com) is where the repo-shaped version starts.
