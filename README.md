# NeutralScan FSA – Gender Neutral Language Recognizer

Web app that finds predefined gender-specific words in a document and suggests
gender-neutral alternatives. Recognition uses a **trie-based deterministic
finite automaton (DFA)** built from the term dictionary.

## Run
1. Open `dist/index.html` in any modern browser (no install, no server).
2. Click **Upload** and choose a file (`samples/sample.txt`), then **Scan language**.

Supports `.txt` (and optionally `.docx` / `.pdf`; those need internet for the reader libraries).

## Samples
`samples/sample.txt` (terms found) · `samples/no-terms.txt` · `samples/empty.txt` · `samples/unsupported.csv`
