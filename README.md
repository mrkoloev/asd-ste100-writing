# ASD-STE100-inspired technical writing


A writing skill for clear technical documentation. It supports drafting, rewriting, reviewing, and summarizing while preserving technical meaning.


This is an independent adaptation of selected ASD-STE100 principles. It is not an official ASD product, a compliance checker, a fact checker, or a substitute for technical review. No official dictionary or standard is bundled. See the [official ASD-STE100 website](https://www.asd-ste100.org/) for the specification.


## Install


The skill instructions are in `SKILL.md` at the repository root. Copy `SKILL.md`, `references/`, and optionally `agents/` into an `asd-ste100-writing/` directory in the personal skills location supported by your AI client. For a Codex installation using the default user skills location, this is `~/.codex/skills/asd-ste100-writing/`.


Other clients may require different discovery paths or invocation syntax. This release does not claim tested compatibility with other clients. The core instructions are plain Markdown and require no external tools.


## Use


Example requests:


- “Use asd-ste100-writing to simplify these instructions without removing conditions or warnings.”
- “Review this technical document. List ambiguities and suggest corrections.”
- “Summarize this report in Russian. Keep key figures and limitations.”
- “Rewrite this English document. Keep the replacement text in English.”


An explicit task takes priority. With material and no task, the skill defaults to rewriting. Summaries require a request. A rewrite keeps the source language unless another language is requested. Commentary follows the conversation language.


The skill preserves program code, commands, identifiers, paths, links, numerical values, and units unless changes are explicitly requested. It flags ambiguity rather than inventing missing facts.


## Evaluation


Use [evals/cases.json](evals/cases.json) to exercise the skill on new models or after changes. Assess the listed criteria, not an exact preferred sentence. Compare runs with and without the skill. Record the client, model, date, and any failures; a structural check alone does not establish behavior or compatibility.


## Contributing


For a proposed change, describe the behavior it improves and include an input that reproduces the problem. Add or update an evaluation case. Keep core instructions concise and examples domain-neutral. Do not add unsupported compatibility or compliance claims.


## License


Copyright 2026 mrkoloev.

Licensed under the [Apache License, Version 2.0](LICENSE). This license covers the original skill instructions, examples, and supporting files in this repository. It does not license the ASD-STE100 standard or grant rights to third-party trademarks.

