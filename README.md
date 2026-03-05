# Ołowiane dzieci — Polish Language Study Companion

A phrase-by-phrase Polish language analysis of *Ołowiane dzieci. Zapomniana epidemia*
by Michał Jędryk — a book about a lead poisoning epidemic in industrial Silesia,
not available in English translation.

## Purpose

This project demonstrates an AI-assisted method for learning a foreign language
through close reading of a genuinely interesting text. The method is described
in full in the compiled document's preface.

## Method summary

- The learner supplies screenshots of the source book one passage at a time
- An AI assistant (Claude Sonnet 4.6 by Anthropic) provides translation,
  word-by-word grammatical breakdown, and literary commentary
- Analyses are consolidated periodically into this LaTeX document
- The document serves both as a study companion and as a transferable record
  of the method for others to adapt

## Repository contents

| File | Contents |
|------|----------|
| `olowiane_dzieci_analiza.tex` | Main file — compile this |
| `preface_ai.tex` | Preface: learner profile, method, and AI transparency note |
| `grammar.tex` | Polish grammar foundations reference |
| `ch00_karta_tytulowa.tex` | Front matter passages (dedication, epigraphs) |
| `ch01_jeszcze_jeden_pogrzeb.tex` | Chapter 1 analysis (in progress) |
| `ch02_`… etc. | Subsequent chapters (added as work progresses) |

## Compiling

Requires a standard TeX Live installation (2022 or later). Compile with pdfLaTeX:

```bash
pdflatex olowiane_dzieci_analiza.tex
pdflatex olowiane_dzieci_analiza.tex   # twice for TOC and cross-references
```

Or open `olowiane_dzieci_analiza.tex` in Texifier / TeXShop / your preferred editor.

## Copyright and fair use

The quoted Polish passages in this document are brief and used solely for
educational commentary, consistent with fair use principles for personal,
non-commercial educational purposes. The source book remains under its
original copyright. This repository contains only the analytical content —
it does not reproduce the source text.

## Adapting this method

The approach works for any language and any text, provided:
- A sufficiently capable LLM is available for that language
- The learner has genuine motivation to read the specific text
- The learner is comfortable with (or willing to learn) basic LaTeX

See the preface in the compiled document for a full discussion.

## Organisation

[SnowdonAnalytica](https://github.com/SnowdonAnalytica)
