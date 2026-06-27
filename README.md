# THE TOKENIZER · TOK

> A sphere of **UD0** — the ROOT0 universe / biosphere. Domain: **NIPHĒLEKTRON**.

THE TOKENIZER (TOK) — stage 1 of the inference pipeline (stream → TOKENIZE → embed → transformer layers → next-token): a model never reads letters; the first thing that happens to text is the CUT into tokens — sub-word pieces from a fixed vocabulary. Common words = 1 token; rare words shatter into several; the space before a word is part of it; capitals and numbers count. Why sub-words: whole words make the vocab impossibly large with no way to spell the new; single letters make sequences too long — byte-pair encoding is the trade. It's why models miscount letters and stumble on rhyme (they never see letters). Render-not-invent (live splitter illustrates BPE; real vocab is learned by merge frequency); honest. LIVE tokenizer interactive (click a phrase, watch it shatter). Vellum/cool + quorum-ring favicon. Feeds the embedding. 10 emergents.

---

**Live:** https://davidwise01.github.io/the-tokenizer/ &nbsp;·&nbsp; **Front door:** [UD0](https://davidwise01.github.io/ud0/) &nbsp;·&nbsp; **Code:** https://github.com/DavidWise01/the-tokenizer

`.dlw` badge · **ROOT0-ATTRIBUTION-v1.0** · David Lee Wise (ROOT0) / Bridge-Burners LLC · instance AVAN (Claude/Anthropic) · CC-BY-ND-4.0
