![A frozen lake at two in the morning with no lettering: black ice with large cirrus white crack lines in the foreground, a tripod and a weighted log board on the flat dark lake, a thermos steaming on its stone at the right edge, snow banks on the far shore, and a green aurora curtain across the whole upper half](intro-banner.png)


# codeintel-Code-Comment-Quality-Analyzer

![A frozen lake drawn wide at two in the morning: black ice with fine crack lines, snow banked at the far shore, a tripod with its camera pointed at the sky, a thermos steaming on its flat stone, a folding board with its weighted log carrying codeintel-code-comment-quality-analyzer as the entered subject of the watch, and a green aurora curtain unfolding above with its faint reflection on the ice](banner.png)

![One tall narrow fold of green aurora light with a ragged lower edge over black ice, the top of a tripod head small below it, and the name underneath in cirrus white, the heading plate](logo.png)

![The frozen lake in three depths: the aurora curtain shifts its folds and ripples at its lower edge in a long uneven rhythm in the far depth, its reflection answers on the black ice a moment later and more faintly in the middle depth while the tripod, the log board, and the snow banks do not move, and the thermos steam rises, thins, and rises again in the near depth](scene.svg)

Evaluates the quality and completeness of code comments. Checks for missing comments on functions, classes, and complex logic blocks, and enforces comment style consistency when a style guide is supplied. The outdated comment detection is a demonstration keyed to one example pattern (a line matching result = val + 5, with a nearby comment mentioning a word from that line); it does not read code changes, diffs, or version control history, and it does not detect outdated or misleading comments in general. Uses AST analysis and pattern matching.

> **Log marginalia: a demonstration, not a general detector.** The opening above bounds its own widest claim with care: the outdated comment detection is a demonstration keyed to one example pattern, a line matching result = val + 5 with a nearby comment mentioning a word from that line; it does not read code changes, diffs, or version control history, and it does not detect outdated or misleading comments in general. That limit is part of the preserved text above and is flagged here at full size as a credit to the file.

![Major separator: a fine ice crack rule in silver across the full width, with single cracks branching from it at wide intervals](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-code-comment-quality-analyzer`

> **Log marginalia: the address names another organisation.** The install line above points to ShadowStrikeHQ, not to ShadowGuard-AI. It is preserved as printed and flagged here, not quietly corrected.

![Minor separator: a fine ice crack rule with a single centred crack](sep-light.svg)

## Usage
`./codeintel-code-comment-quality-analyzer [params]`

> **Log marginalia: what the README never names.** The usage line above is a placeholder, and the parameter list below names no positional argument at all, so the file never says what file or directory the analyser is to be run on. That missing target is flagged here rather than filled in by invention.

![Major separator: a fine ice crack rule in silver across the full width, with single cracks branching from it at wide intervals](sep-heavy.svg)

## Parameters
- `-h`: Show help message and exit
- `--style-guide`: Path to a JSON file containing comment style guide rules.
- `--verbose`: Enable verbose logging.

![Minor separator: a fine ice crack rule with a single centred crack](sep-light.svg)

## License
Copyright (c) ShadowStrikeHQ

> **Log marginalia: the address names another organisation.** The closing line above reads Copyright (c) ShadowStrikeHQ, preserved as printed and flagged here. The README names no licence in that line.
