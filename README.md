![Banner](banner.png)

# codeintel-Code-Comment-Quality-Analyzer
Evaluates the quality and completeness of code comments. Checks for missing comments on functions, classes, and complex logic blocks, and enforces comment style consistency when a style guide is supplied. The outdated comment detection is a demonstration keyed to one example pattern (a line matching result = val + 5, with a nearby comment mentioning a word from that line); it does not read code changes, diffs, or version control history, and it does not detect outdated or misleading comments in general. Uses AST analysis and pattern matching.

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-code-comment-quality-analyzer`

## Usage
`./codeintel-code-comment-quality-analyzer [params]`

## Parameters
- `-h`: Show help message and exit
- `--style-guide`: Path to a JSON file containing comment style guide rules.
- `--verbose`: Enable verbose logging.

## License
Copyright (c) ShadowStrikeHQ
