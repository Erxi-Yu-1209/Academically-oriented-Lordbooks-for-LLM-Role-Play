# SillyTavern Book-Derived Reasoning World Books


[ English ](README.md) &nbsp;•&nbsp; [ 简体中文 ](README-zh.md)

**A collection of modular SillyTavern World Books (Lorebooks) that translate from classic academic monographs, historical micro-studies, sociology, moral philosophy, and literary works.**


## Overview

When running long-form roleplay in [SillyTavern](https://github.com/SillyTavern/SillyTavern), Large Language Models (LLMs) often fall back on flattened tropes: empires feel like modern corporate HR departments, medieval churches act like generic fantasy cults, moral dilemmas resolve through painless speeches, and gender or relationship dynamics collapse into rigid, cliché templates.

This repository houses **specialized World Books (`.json`)** designed to solve that problem at the architectural level. Instead of stuffing static encyclopedia lore into your prompt, each World Book converts specific published books—ranging from Judith Butler, Michel Foucault, and Ursula K. Le Guin to H. L. A. Hart, Carl Schmitt, James C. Scott, Pierre Bourdieu, Ernst Kantorowicz, Max Weber, Carlo Ginzburg, Jonathan Wolff, and George Herbert Mead—into **executable narrative constraints and secondary reasoning modules**.

Every World Book in this repository combines two distinct layers of entries:
1. **General Chain-of-Thought (CoT) & System Control Entries**: Master routing engines, worldview terminology translators, ethical logic gates, three-layer consequence ledgers, Gestalt psychological cycles, and dynamic living-world rules (`[Living World]`, `[SELF-REASONING]`). These govern *how* the LLM selects mechanisms, prevent academic jargon from leaking into visible dialogue, and enforce epistemic boundaries (such as anti-omniscience).
2. **Book-Derived Secondary Reasoning Entries**: Granular domain modules distilled chapter-by-chapter or concept-by-concept from specific published books. These activate when matching themes appear in the story—turning abstract theory into concrete pressures on bodies, budgets, courtrooms, rumors, supply lines, and interpersonal gestures.

## Repository Structure & World Book Index

Each World Book lives in its own dedicated sub-directory with full bilingual documentation (`README.md` and `README-zh.md`) that cross-references every `[Code]` prefix, `UID`, roleplay function, and source publication.

| No. | World Book Title (EN / ZH) | Sub-directory Documentation | Source JSON File | Entries (Constant / Keyword) | Primary Narrative Role & Core Source Foundations |
| :---: | :--- | :--- | :--- | :---: | :--- |
| **01** | **Gender De-stereotyping 2.0**<br>*(性别去刻板印象化2.0)* | [English](https://www.google.com/search?q=./Gender-De-stereotyping-2.0/README.md) · [中文](https://www.google.com/search?q=./Gender-De-stereotyping-2.0/README-zh.md) | `Gender De-stereotyping 2.0.json`<br>`性别去刻板印象化2.0.json` | **19**<br>*(19 Constant / 0 Keyword)* | **Always-on gender, kinship, and bodily de-stereotyping engine.** Replaces formulaic gender/romance clichés with performativity, vulnerability, disciplinary institutions, and non-binary anthropological worldbuilding *(Butler, Foucault, Derrida/Watkin, Le Guin)*. |
| **02** | **Macro Spacetime**<br>*(宏观时空)* | [English](https://www.google.com/search?q=./Macro-Spacetime/README.md) · [中文](https://www.google.com/search?q=./Macro-Spacetime/README-zh.md) | `Macro Spacetime.json`<br>`宏观时空.json` | **154**<br>*(5 Constant / 149 Keyword)* | **Cross-worldview macro-sociological & political reasoning engine.** Governs law, sovereignty, empire/periphery, hidden transcripts, social movements, revolutions, scientific paradigms, habitus/field, modes of production, and dynamic living-world physics across fantasy, sci-fi, and political RP *(Hart, Schmitt, Said, Scott, Zhao Dingxin, Skocpol, Lévi-Strauss, Wolff, Zhou Xueguang, Agamben, Kuhn, Giddens, Bourdieu, Althusser, Foucault, Derrida/Watkin, Engels, Conrad)*. |
| **03** | **Middle Ages**<br>*(中世纪)* | [English](https://www.google.com/search?q=./Middle-Ages/README.md) · [中文](https://www.google.com/search?q=./Middle-Ages/README-zh.md) | `Middle Ages.json`<br>`中世纪.json` | **88**<br>*(0 Constant / 88 Keyword)* | **Zero-overhead historical & dark-fantasy institutional engine.** 100% keyword-triggered modules for the King's Two Bodies, Reformation commercial sects, inquisitorial microhistory, Purgatory geography, Loudun possession theater, Gévaudan monster panics, Roman equestrian bureaucracy, state cybernetics, and a 20-part Teutonic Military Order mystery system *(Kantorowicz, Weber, Ginzburg, Le Goff, Huxley, Jay M. Smith, Davenport, Medina, Foucault, Nicholas Morton)*. |
| **04** | **Moral Ethics 2.1**<br>*(道德伦理学2.1)* | [English](https://www.google.com/search?q=./Moral-Ethics-2.1/README.md) · [中文](https://www.google.com/search?q=./Moral-Ethics-2.1/README-zh.md) | `Moral Ethics 2.1.json`<br>`道德伦理学2.1.json` | **72**<br>*(3 Constant / 69 Keyword)* | **Normative moral philosophy & micro-psychological interaction engine.** Combines a `{{MoralPressure}}` logic gate, `<think>` ethical CoT, and `<Moral_Audit>` ledger with 15 chapters of moral philosophy, 42 chapters of symbolic interactionism (`I` vs. `Me`), generative linguistics, technologies of the self, Gestalt therapy, and trauma misrecognition *(Wolff, Mead, Chomsky, Foucault, Derrida/Watkin, Gestalt Therapy)*. |

## How SillyTavern World Books Work

* **Constant Entries (`constant: true`, 🔵 Blue Light in SillyTavern):** Injected on every turn regardless of chat keywords. In these World Books, only lightweight master routers, terminology translators, anti-omniscience guards, and compact global engines (such as the 19 entries in `Gender De-stereotyping 2.0`) are set to Constant so your baseline token budget stays lean.
* **Keyword-Triggered Entries (`constant: false`, `selective: true`, 🟢 Green Light in SillyTavern):** Stored dormant on disk and injected *only* when the user's input or recent chat turns match the entry's keyword array (`key`). This allows `Macro Spacetime` (154 entries), `Middle Ages` (88 entries), and `Moral Ethics 2.1` (72 entries) to hold ratusan of pages of distilled academic logic while activating only the 2–5 modules relevant to the current scene.
* **Injection Depth (`depth: 0` to `4`) & Insertion Order (`order`):**
  * `@D4` (4 messages before the bottom of the chat history) and `@D3` hold foundational structural frameworks and background rules.
  * `@D2` and `@D1` hold near-field scene resolvers, psychological defenses, and three-layer consequence ledgers.
  * `@D0` (the very bottom of the prompt, right before generation) holds high-priority master gates and `<think>` Chain-of-Thought verification templates.
* **Anti-Jargon Translation Rule:** Every World Book in this repository enforces a strict separation between **internal reasoning** and **visible prose**. The LLM uses these entries as a physics engine to calculate *who pays the cost, who hides a ledger, whose body hesitates, and how an institution reacts*, but translates those mechanisms into natural sensory details, period-appropriate speech, and concrete actions—never academic lectures.

## Summary of the World Books

### 1. Gender De-stereotyping 2.0 (`性别去刻板印象化2.0`)
* **Directory:** [./Gender-De-stereotyping-2.0/README.md](https://www.google.com/search?q=./Gender-De-stereotyping-2.0/README.md) | [./Gender-De-stereotyping-2.0/README-zh.md](https://www.google.com/search?q=./Gender-De-stereotyping-2.0/README-zh.md)
* **Design:** 19 permanently active entries (`14 @D4`, `5 @D2`) built around Judith Butler's *Gender Trouble* and *Undoing Gender*, Michel Foucault's *The History of Sexuality (Vols. 1–3)* and *Ethics: Subjectivity and Truth*, Christopher Watkin's *Jacques Derrida*, and Ursula K. Le Guin's *The Left Hand of Darkness* / *"Is Gender Necessary? Redux"*.
* **Use Case:** Prevents the LLM from reducing characters to stereotypical gender roles or biological determinism. Includes a silent 5-step scene checker (`[BUTLER:CHECKLIST]`) and Le Guin's thought-experiment engines for non-patriarchal or non-binary speculative worlds.

### 2. Macro Spacetime (`宏观时空`)
* **Directory:** [./Macro-Spacetime/README.md](https://www.google.com/search?q=./Macro-Spacetime/README.md) | [./Macro-Spacetime/README-zh.md](https://www.google.com/search?q=./Macro-Spacetime/README-zh.md)
* **Design:** 154 entries (`5 Constant` core routers + `149 Keyword-Triggered` modules) integrating 18 major academic works alongside the `[CORE:ALL]` routing engine and the `[Living World]` (`[活的世界]`) anti-omniscience and physical conflict system.
* **Use Case:** Ideal for grand political intrigue, empire-building, colonial frontiers, rebellions, scientific/magical academy rivalries, and socio-economic worldbuilding across any genre (fantasy, sci-fi, cyberpunk, alternate history, or historical fiction). Automatically translates setting-native terms (e.g., *dragon pact*, *inquisition*, *corporate board*, *mana tax*) into institutional mechanics and forces every macro event to land across three concrete layers (Direct, Institutional, and Everyday).

### 3. Middle Ages (`中世纪`)
* **Directory:** [./Middle-Ages/README.md](https://www.google.com/search?q=./Middle-Ages/README.md) | [./Middle-Ages/README-zh.md](https://www.google.com/search?q=./Middle-Ages/README-zh.md)
* **Design:** 88 keyword-triggered entries (`0 Constant`) split out from the macro framework and expanded to provide specialized medieval, early-modern, and dark-fantasy institutional depth without consuming permanent context tokens.
* **Use Case:** Activates on demand when a story touches royal coronations or depositions (*Kantorowicz*), ascetic Protestant merchants and sect credit (*Weber*), peasant heresies and inquisitorial archives (*Ginzburg*), the geography and economy of Purgatory (*Le Goff*), convent possession scandals and exorcism media (*Huxley*), frontier beast panics (*Jay M. Smith*), Roman equestrian officer-bureaucrats (*Davenport*), state control rooms (*Medina*), multi-discourse murder dossiers (*Foucault*), or a 20-entry Teutonic Military Order institutional mystery engine (*Nicholas Morton*).

### 4. Moral Ethics 2.1 (`道德伦理学2.1`)
* **Directory:** [./Moral-Ethics-2.1/README.md](https://www.google.com/search?q=./Moral-Ethics-2.1/README.md) | [./Moral-Ethics-2.1/README-zh.md](https://www.google.com/search?q=./Moral-Ethics-2.1/README-zh.md)
* **Design:** 72 entries (`3 Constant` gates/engines + `69 Keyword-Triggered` chapters and patches) uniting Jonathan Wolff's *An Introduction to Moral Philosophy* (15 chapters), George Herbert Mead's *Mind, Self, and Society* (42 chapters), Noam Chomsky's *Language and Mind*, Michel Foucault's *Technologies of the Self*, Jacques Derrida's deconstructive ethics, clinical *Gestalt Therapy*, and the original `[SELF-REASONING]` trauma-bias module.
* **Use Case:** Deepens character interiority, moral conflict, and interpersonal friction. Dynamically switches between silent background tracking during peaceful scenes (`MoralPressure < 70`) and full `<think>` ethical Chain-of-Thought + `<Moral_Audit>` balance-sheet tracking during high-stakes betrayals, sacrifices, or coercion (`MoralPressure >= 70`).
