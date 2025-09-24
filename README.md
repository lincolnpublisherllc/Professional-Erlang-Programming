README (as requested, outside the ZIP)
What’s inside

15 folders: Chapter_01 … Chapter_15

446 code files total, grouped by the chapter where they appear

A MANIFEST.csv in the ZIP root listing chapter, file path, size, lines, and detected type

Counts by chapter

01: 44 files

02: 45 files

03: 40 files

04: 30 files

05: 23 files

06: 44 files

07: 33 files

08: 29 files

09: 27 files

10: 20 files

11: 12 files

12: 21 files

13: 47 files

14: 15 files

15: 16 files

File naming

Snippets are sequential per chapter: snippet_001.erl, snippet_002.yml, snippet_003.sh, etc.

When a Dockerfile was detected, it’s named like snippet_005_Dockerfile.

Extensions were inferred from content:

.erl for Erlang modules and snippets that include -module(, -export(, etc.

.yml for CI and YAML configs

.sh for shell scripts and shebangs

Dockerfile for Docker recipes

.config / .json / .ini / .sql / .txt where appropriate

How I detected code (so you know what’s included)

Looked for chapter headers like “Chapter 1”, “Chapter 2”, etc., then grouped paragraphs until the next chapter.

Tagged paragraphs as code if they:

used a “Code” or monospaced style, or

started with typical code patterns (Erlang -module(, %% comments, rebar3/relx, GitHub Actions YAML keys, Dockerfile instructions, shebangs), or

had heavy symbol density or indentation consistent with source.

Consecutive code paragraphs were merged into a single snippet file.

Quick start

Erlang snippets: you can copy .erl files into an OTP app and compile with rebar3 compile.

Configs: drop rebar.config fragments into your umbrella as needed; CI YAML can go into .github/workflows.

Dockerfile and scripts: place into docker/ or your build context and adjust paths as needed.

Notes and caveats

Some listings in the book are partial or annotated for teaching. They extract exactly as shown, so you may need to integrate them into your project structure.

If a snippet didn’t clearly signal a language, it’s saved as .txt to avoid guessing wrong.

Use the MANIFEST.csv to locate a file quickly and see its basic metadata.

If you want me to normalize filenames by topic (for example api_guard_transform.erl, json_logger_h.erl, build_info.erl) or stitch related fragments into complete modules, say the word and I’ll reorganize the package to your preference.

Professional Erlang Programming
