<div align="center">

[![abysssol's GitHub Stats](https://github-readme-stats.vercel.app/api?username=abysssol&show=reviews,prs_merged_percentage&theme=vision-friendly-dark&show_icons=true&border_radius=16)](https://github.com/anuraghazra/github-readme-stats)
[![abysssol's Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=abysssol&size_weight=1.1&count_weight=0.7&layout=donut&langs_count=7&theme=vision-friendly-dark&show_icons=true&border_radius=16)](https://github.com/anuraghazra/github-readme-stats)

</div>

I have a particular interest in game design, originally learning programming so I could create a video game, though got distracted learning about efficient programming patterns and algorithm design, then learned Rust, moved to Debian (Linux) as a primary operating system, then to Arch Linux, and finally discovered and settled on Nixos, gradually learning more advanced usage of Nix. I have more recently started to seriously consider focusing on game development and producing a real, playable game available on Steam and other platforms (I have made several prototypes before, but they never amounted to much).

I am also interested in programming language design, especially liking machine checked correctness (think Rust and Haskell) with a casual interest in formal verification (particularly [Magmide](https://github.com/magmide/magmide)). I also like studying how to design powerful features (like macros, traits/interfaces/typeclasses, async, etc) in a user-friendly manner that is as easy to use and as simple as possible, without sacrificing too much capability (such as optional, incremental levels of complexity that can be easily accessed if necessary, but are "hidden" by default).

I care most about code correctness and almost as much about performance, with a secondary focus on ease of use, perceptual simplicity, feature completeness, and good documentation. I think that good documentation is too often underestimated, to the great detriment of all (look to Rust for an unfortunately uncommon example of high quality, easily accessible, and (mostly) comprehensive documentation).

Please contact me at <abysssol@pm.me> if you want to introduce me to a new project, collaborate with me, hire me, or just show me something cool that you like.

Here are some things that I currently do and want to start doing:

- I currently maintain the Nix [package][ollama package] and [module][ollama module] for [Ollama][ollama]. I originally began by bringing it up to date after significant upstream changes had caused it to become quite outdated. See my pull requests for nixpkgs [here][prs], my reviews on other's pull requests [here][reviews], and issues I've helped with [here][issues].

[ollama package]: https://search.nixos.org/packages?channel=unstable&from=0&size=50&sort=relevance&type=packages&query=ollama
[ollama module]: https://search.nixos.org/options?channel=unstable&from=0&size=50&sort=relevance&type=packages&query=services.ollama.
[ollama]: https://github.com/ollama/ollama
[prs]: https://github.com/NixOS/nixpkgs/pulls?q=is%3Apr+author%3Aabysssol
[reviews]: https://github.com/NixOS/nixpkgs/pulls?q=is%3Apr+involves%3Aabysssol++-author%3Aabysssol
[issues]: https://github.com/NixOS/nixpkgs/issues?q=is%3Aissue+involves%3Aabysssol

- I know Rust well, and want to work more with Rust, both contributing to others' projects, as well as my own new projects

- I want to begin developing a video game, probably in Rust, in one of a few possible genres
  - top down, story driven, action rpg, bullet heaven, dungeon crawler (Path of Exile + Nova Drift + Vampire Survivors + Reverend Insanity (webnovel))
  - side scrolling, action stealth, metroidvania (Mark of the Ninja + Hollow Knight)
  - voxel based, survival, exploration, incremental, base building, automation (Valheim + Minecraft + Terraria + Satisfactory + Astroneer)
  - text/ui based, story driven, adventure, rpg, incremental, exploration (A Dark Room + Universal Paperclips + Dwarf Fortress + Ngu Idle + Your Chronicle + that one game I played on Kongregate 6+ years back but can't find anymore)

- I am interested in programming language design, and want to explore what a simple and easy programming language (think Python) would look like with modern optimizations, features, and static type system
  - hybrid compile-runtime garbage collector, using Rust style borrow checking transparently when possible, falling back to garbage collection utilizing compile time information to fine-tune allocation size and location based on type size, locations used in algorithms, etc
  - automatic transparent concurrency and parallelism (from analyzing data flow and computation dependencies), as can be found in Data Parallel Haskell (extension), [Bend](https://github.com/HigherOrderCO/Bend), and [Mojo](https://github.com/modularml/mojo)
  - automatic data structure optimization, such as transparently transforming a list of "structures"/"records" into multiple lists to minimize padding/wasted bytes and bits, as well as other data packing techniques like automatically packing booleans and other sub-byte-sized types together,  which is important for cache optimization.
    - Also automatically altering list or map/table implementation based on heuristics, for example choosing between hashing or btree maps based on known performance characteristics, even switching between implementations at runtime based on map size or branch taken
    - Automatically optimizing functional code with immutable data into machine code that mutates memory to improve performance and memory usage (Rust's borrow checking technique should help here)
  - optional easy code verification/proofs (hopefully built on top of [Magmide](https://github.com/magmide/magmide) if it succeeds)
  - custom assembly/machine code generation based on compile time information that isn't usable in llvm if [Magmide](https://github.com/magmide/magmide) never happens
 
- I have several ideas for a novel, mostly science fiction, also fantasy
  - I'm seriously considering creating an extensive edit of Reverend Insanity for better readability in English. I would develop a small complementary program to allow different versions to be generated, like toggling transliterated names on or off

- I would start a youtube channel (and/or blog), but I'm not really sure what people might be interested in, and what topics are currently lacking adequate coverage. If you have any ideas or suggestions on what would interest you, please email me and tell me! I'd love to hear what topics you're interested in that you can't find enough content on.
