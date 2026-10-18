**LFC Foundry** is a home for open source web apps, games and the small JavaScript pieces they are built from. Each app or game is a single `.html` file that runs entirely in the browser: you download the file once and open it, with no server, account or install. The pieces (modules and tools) are one dependency-free file each that any single-file page can copy in, and every one is built and tested by a person pairing with AI.

## Why it exists

Software for the web has drifted toward accounts, tracking, ads and a pile of dependencies that stop working when a server goes away. We wanted a place where a useful tool or a good game is one file you can keep forever, and where the small parts behind it are shared in the open so others can reuse and adapt them. Three pillars follow from that:
* 📦 **Local-First Client (LFC):** Every utility, tool, or game is contained entirely within a single `.html` file or executable. 
* 🔌 **Zero Network Footprint:** No accounts, no data tracking, and zero ads. Download a file once, and it will run 100% offline in any modern browser forever.
* 🤖 **Human-AI Collaboration:** We leverage advanced AI pairing workflows to rapidly prototype, stress-test, and smelt raw logic into hardened, modular vanilla CSS and JavaScript.

## 🧰 What's inside

**Games and apps** (each one is a single `.html` file): [Apple Press](https://github.com/lfcfoundry/apple-press) ([play](https://lfcfoundry.github.io/apple-press/)), [Fancy, the Banana](https://github.com/lfcfoundry/fancy-banana) ([play](https://lfcfoundry.github.io/fancy-banana/)), [Pineapple Defense](https://github.com/lfcfoundry/pineapple-defense) and the [Story Editor](https://github.com/lfcfoundry/story-editor).

**[JS-modules](https://github.com/lfcfoundry/JS-modules)** are small, dependency-free pieces that any single-file page can copy in, with live demos at https://lfcfoundry.github.io/JS-modules/. Every one has a README, a changelog and a size; the [full tables](https://github.com/lfcfoundry/JS-modules#pick-a-piece) list the file size of each.

**Modules & Tools (38)**

* Device and browser adaptation: [env-probes](https://github.com/lfcfoundry/JS-modules/blob/main/modules/env-probes/README.md), [frame-kit](https://github.com/lfcfoundry/JS-modules/blob/main/modules/frame-kit/README.md), [fx-governor](https://github.com/lfcfoundry/JS-modules/blob/main/modules/fx-governor/README.md), [slow-note](https://github.com/lfcfoundry/JS-modules/blob/main/modules/slow-note/README.md)
* Saving and data safety: [save-kit](https://github.com/lfcfoundry/JS-modules/blob/main/modules/save-kit/README.md), [tab-guard](https://github.com/lfcfoundry/JS-modules/blob/main/modules/tab-guard/README.md)
* Games - Looks and effects: [cartoon-3d-kit](https://github.com/lfcfoundry/JS-modules/blob/main/modules/cartoon-3d-kit/README.md), [fly-to-mini](https://github.com/lfcfoundry/JS-modules/blob/main/modules/fly-to-mini/README.md), [sprite-baker](https://github.com/lfcfoundry/JS-modules/blob/main/modules/sprite-baker/README.md), [stage-curtains](https://github.com/lfcfoundry/JS-modules/blob/main/modules/stage-curtains/README.md), [sticker-text](https://github.com/lfcfoundry/JS-modules/blob/main/modules/sticker-text/README.md)
* Games - Controls: [back-close](https://github.com/lfcfoundry/JS-modules/blob/main/modules/back-close/README.md), [hold-press](https://github.com/lfcfoundry/JS-modules/blob/main/modules/hold-press/README.md), [pad-nav](https://github.com/lfcfoundry/JS-modules/blob/main/modules/pad-nav/README.md), [wake-keeper](https://github.com/lfcfoundry/JS-modules/blob/main/modules/wake-keeper/README.md)
* Games - Assist: [grown-ups-door](https://github.com/lfcfoundry/JS-modules/blob/main/modules/grown-ups-door/README.md), [spotlight-tour](https://github.com/lfcfoundry/JS-modules/blob/main/modules/spotlight-tour/README.md)
* Games - Math: [idle-core](https://github.com/lfcfoundry/JS-modules/blob/main/modules/idle-core/README.md)
* Games - Testing: [canvas-probe](https://github.com/lfcfoundry/JS-modules/blob/main/tools/canvas-probe/README.md), [firefox-stand-in](https://github.com/lfcfoundry/JS-modules/blob/main/tools/firefox-stand-in/README.md), [fuzz-kit](https://github.com/lfcfoundry/JS-modules/blob/main/tools/fuzz-kit/README.md), [speed-lab](https://github.com/lfcfoundry/JS-modules/blob/main/tools/speed-lab/README.md), [storage-probe](https://github.com/lfcfoundry/JS-modules/blob/main/tools/storage-probe/README.md), [test-isolation](https://github.com/lfcfoundry/JS-modules/blob/main/tools/test-isolation/README.md), [webkit-driver](https://github.com/lfcfoundry/JS-modules/blob/main/tools/webkit-driver/README.md)
* App - Efficiency: [memory-compression](https://github.com/lfcfoundry/JS-modules/blob/main/modules/memory-compression/README.md), [single-file-tools](https://github.com/lfcfoundry/JS-modules/blob/main/tools/single-file-tools/README.md)
* Model simulation: [walker-sim](https://github.com/lfcfoundry/JS-modules/blob/main/modules/walker-sim/README.md)
* Visualization: [gif-writer](https://github.com/lfcfoundry/JS-modules/blob/main/modules/gif-writer/README.md), [netflow-engine](https://github.com/lfcfoundry/JS-modules/blob/main/modules/netflow-engine/README.md), [netflow-layers](https://github.com/lfcfoundry/JS-modules/blob/main/modules/netflow-layers/README.md), [netflow-sankey](https://github.com/lfcfoundry/JS-modules/blob/main/modules/netflow-sankey/README.md)
* Size and packaging: [lzma-decode](https://github.com/lfcfoundry/JS-modules/blob/main/modules/lzma-decode/README.md), [lzma-pack](https://github.com/lfcfoundry/JS-modules/blob/main/tools/lzma-pack/README.md), [pcodec-js](https://github.com/lfcfoundry/JS-modules/blob/main/modules/pcodec-js/README.md), [ppmd-decode](https://github.com/lfcfoundry/JS-modules/blob/main/modules/ppmd-decode/README.md), [ppmd-pack](https://github.com/lfcfoundry/JS-modules/blob/main/tools/ppmd-pack/README.md), [zip-open](https://github.com/lfcfoundry/JS-modules/blob/main/modules/zip-open/README.md)

**Story Editor packages (10)**

* Story data: [story-diff](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-diff/README.md), [story-format](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-format/README.md), [story-outline](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-outline/README.md), [twine-import](https://github.com/lfcfoundry/story-editor/blob/main/packages/twine-import/README.md)
* Story validation: [story-check](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-check/README.md)
* Story flow: [story-map](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-map/README.md)
* Story build and distribute: [story-player](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-player/README.md)
* Story packaging: [zip-page](https://github.com/lfcfoundry/story-editor/blob/main/packages/zip-page/README.md)
* Story testing: [contract-kit](https://github.com/lfcfoundry/story-editor/blob/main/packages/contract-kit/README.md), [qa-kit](https://github.com/lfcfoundry/story-editor/blob/main/packages/qa-kit/README.md)

**AI knowledge base (1)**

* Working with an AI helper: [ai-collab-kit](https://github.com/lfcfoundry/story-editor/blob/main/packages/ai-collab-kit/README.md)

---

## 📜 Open Source & Branding Policy

All software produced by the LFC Foundry is distributed under the **MIT License**. You are completely free to use, modify, fork, and even commercially monetize the code. 

### ⚠️ Trademark & Attribution Notice
While the underlying source code is open, the names **"LFC Foundry"**, **"LFC Core"**,  **"JNFoo"**,and our project branding are reserved identifiers. 
* If you fork or redistribute our files, you **must preserve the original copyright notice** inside the file comments as required by the MIT License.
* If you modify our applications to launch your own downstream or commercial product, you **must change the brand name** and remove the LFC Foundry identity from your user interface.

📍 *Built for the permanent, independent web.*
