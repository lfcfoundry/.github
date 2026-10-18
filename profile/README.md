Welcome to the **LFC Foundry**. We build single-file, highly-optimized web applications and minimalist games engineered to run entirely client-side. 

Our philosophy is built on three core pillars:
* 📦 **Local-First Client (LFC):** Every utility, tool, or game is contained entirely within a single `.html` file or executable. 
* 🔌 **Zero Network Footprint:** No accounts, no data tracking, and zero ads. Download a file once, and it will run 100% offline in any modern browser forever.
* 🤖 **Human-AI Collaboration:** We leverage advanced AI pairing workflows to rapidly prototype, stress-test, and smelt raw logic into hardened, modular vanilla CSS and JavaScript.

## 🧰 What's inside

**Games and apps** (each one is a single `.html` file): [Apple Press](https://github.com/lfcfoundry/apple-press) ([play](https://lfcfoundry.github.io/apple-press/)), [Fancy, the Banana](https://github.com/lfcfoundry/fancy-banana) ([play](https://lfcfoundry.github.io/fancy-banana/)), [Pineapple Defense](https://github.com/lfcfoundry/pineapple-defense) and the [Story Editor](https://github.com/lfcfoundry/story-editor).

**[JS-modules](https://github.com/lfcfoundry/JS-modules)** are small, dependency-free pieces that any single-file page can copy in, with live demos at https://lfcfoundry.github.io/JS-modules/. Every one has a README, a changelog and a size; the [full tables](https://github.com/lfcfoundry/JS-modules#pick-a-piece) list the file size of each.

**26 modules for games and apps**

* Saving and data safety: [save-kit](https://github.com/lfcfoundry/JS-modules/blob/main/modules/save-kit/README.md)
* Device and browser adaptation: [env-probes](https://github.com/lfcfoundry/JS-modules/blob/main/modules/env-probes/README.md), [fx-governor](https://github.com/lfcfoundry/JS-modules/blob/main/modules/fx-governor/README.md), [frame-kit](https://github.com/lfcfoundry/JS-modules/blob/main/modules/frame-kit/README.md), [slow-note](https://github.com/lfcfoundry/JS-modules/blob/main/modules/slow-note/README.md)
* Controls: [hold-press](https://github.com/lfcfoundry/JS-modules/blob/main/modules/hold-press/README.md), [pad-nav](https://github.com/lfcfoundry/JS-modules/blob/main/modules/pad-nav/README.md), [tab-guard](https://github.com/lfcfoundry/JS-modules/blob/main/modules/tab-guard/README.md), [wake-keeper](https://github.com/lfcfoundry/JS-modules/blob/main/modules/wake-keeper/README.md), [back-close](https://github.com/lfcfoundry/JS-modules/blob/main/modules/back-close/README.md)
* First visit and grown-ups: [grown-ups-door](https://github.com/lfcfoundry/JS-modules/blob/main/modules/grown-ups-door/README.md), [spotlight-tour](https://github.com/lfcfoundry/JS-modules/blob/main/modules/spotlight-tour/README.md)
* Looks and effects: [stage-curtains](https://github.com/lfcfoundry/JS-modules/blob/main/modules/stage-curtains/README.md), [fly-to-mini](https://github.com/lfcfoundry/JS-modules/blob/main/modules/fly-to-mini/README.md), [sticker-text](https://github.com/lfcfoundry/JS-modules/blob/main/modules/sticker-text/README.md), [sprite-baker](https://github.com/lfcfoundry/JS-modules/blob/main/modules/sprite-baker/README.md), [cartoon-3d-kit](https://github.com/lfcfoundry/JS-modules/blob/main/modules/cartoon-3d-kit/README.md)
* Game math: [idle-core](https://github.com/lfcfoundry/JS-modules/blob/main/modules/idle-core/README.md)
* Size and packaging: [lzma-decode](https://github.com/lfcfoundry/JS-modules/blob/main/modules/lzma-decode/README.md), [ppmd-decode](https://github.com/lfcfoundry/JS-modules/blob/main/modules/ppmd-decode/README.md)
* Files, charts and simulation: [gif-writer](https://github.com/lfcfoundry/JS-modules/blob/main/modules/gif-writer/README.md), [zip-open](https://github.com/lfcfoundry/JS-modules/blob/main/modules/zip-open/README.md), [memory-compression](https://github.com/lfcfoundry/JS-modules/blob/main/modules/memory-compression/README.md), [netflow-sankey](https://github.com/lfcfoundry/JS-modules/blob/main/modules/netflow-sankey/README.md), [netflow-layers](https://github.com/lfcfoundry/JS-modules/blob/main/modules/netflow-layers/README.md), [walker-sim](https://github.com/lfcfoundry/JS-modules/blob/main/modules/walker-sim/README.md)

**11 packages in the Story Editor repo** (story data, checking, drawing, playing, and the tools that build them)

* Story data: [story-format](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-format/README.md), [twine-import](https://github.com/lfcfoundry/story-editor/blob/main/packages/twine-import/README.md), [story-outline](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-outline/README.md), [story-diff](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-diff/README.md)
* Checking: [story-check](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-check/README.md)
* Drawing: [story-map](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-map/README.md)
* Playing and building: [story-player](https://github.com/lfcfoundry/story-editor/blob/main/packages/story-player/README.md)
* Tools for the story editor: [zip-page](https://github.com/lfcfoundry/story-editor/blob/main/packages/zip-page/README.md), [qa-kit](https://github.com/lfcfoundry/story-editor/blob/main/packages/qa-kit/README.md), [contract-kit](https://github.com/lfcfoundry/story-editor/blob/main/packages/contract-kit/README.md), [ai-collab-kit](https://github.com/lfcfoundry/story-editor/blob/main/packages/ai-collab-kit/README.md)

**10 tools for games** (packing a page smaller, testing in real browsers, speed checks)

* [lzma-pack](https://github.com/lfcfoundry/JS-modules/blob/main/tools/lzma-pack/README.md), [ppmd-pack](https://github.com/lfcfoundry/JS-modules/blob/main/tools/ppmd-pack/README.md), [single-file-tools](https://github.com/lfcfoundry/JS-modules/blob/main/tools/single-file-tools/README.md), [fuzz-kit](https://github.com/lfcfoundry/JS-modules/blob/main/tools/fuzz-kit/README.md), [canvas-probe](https://github.com/lfcfoundry/JS-modules/blob/main/tools/canvas-probe/README.md), [storage-probe](https://github.com/lfcfoundry/JS-modules/blob/main/tools/storage-probe/README.md), [firefox-stand-in](https://github.com/lfcfoundry/JS-modules/blob/main/tools/firefox-stand-in/README.md), [test-isolation](https://github.com/lfcfoundry/JS-modules/blob/main/tools/test-isolation/README.md), [speed-lab](https://github.com/lfcfoundry/JS-modules/blob/main/tools/speed-lab/README.md), [webkit-driver](https://github.com/lfcfoundry/JS-modules/blob/main/tools/webkit-driver/README.md)

---

## 📜 Open Source & Branding Policy

All software produced by the LFC Foundry is distributed under the **MIT License**. You are completely free to use, modify, fork, and even commercially monetize the code. 

### ⚠️ Trademark & Attribution Notice
While the underlying source code is open, the names **"LFC Foundry"**, **"LFC Core"**,  **"JNFoo"**,and our project branding are reserved identifiers. 
* If you fork or redistribute our files, you **must preserve the original copyright notice** inside the file comments as required by the MIT License.
* If you modify our applications to launch your own downstream or commercial product, you **must change the brand name** and remove the LFC Foundry identity from your user interface.


📍 *Built for the permanent, independent web.*
