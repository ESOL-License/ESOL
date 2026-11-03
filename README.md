# Ethical Security Operations License (ESOL)

**Current version:** [ESOL v2.1](./ESOL_v2.1.md) | **Jurisdiction:** Germany (Berlin)
**Maintainer:** [@VolkanSah](https://github.com/VolkanSah) & @BadTin and some Cats

ESOL is a usage license that is added **on top of** a base license (MIT, Apache 2.0, and others). The base license governs copying and modification of code. ESOL governs the ethical and legal **use** of the Work: no fraud, no weapons, no unauthorized security operations, no parasitism, and no AI training for closed-source models without consent.

> **Status note:** Licenses with usage restrictions do not meet the Open Source Definition (OSI, point 6). Software under ESOL is "source available" or "ethical source", not "Open Source" in the strict sense.

## AI training reservation

Everyone may use the code, also to train **open models** (public weights under a free license). Training of **closed models** needs written consent. Text and data mining for closed-model training is reserved (Art. 4 Directive (EU) 2019/790, § 44b UrhG) and declared in [ai.txt](./ai.txt). Assistive Use stays free. Crawlers cannot check whether a model will be open, so `ai.txt` disallows automated crawling; open-model trainers rely on the license. Note: `robots.txt` only works at the root of a domain, GitHub does not serve it for repositories, so the license text and `ai.txt` are the reservation here.

## Versions

| Version | File | Status |
|---|---|---|
| **2.1** | [ESOL_v2.1.md](./ESOL_v2.1.md) | Current |
| 2.0 | [ESOL_v2.0.md](./ESOL_v2.0.md) | Original release, archived unchanged. Releases published under 2.0 remain under 2.0. |

<details>
<summary>What's new in v2.1</summary>

- Back to the voice of v2.0, including the **Psychological Barrier** (Section 5)
- One single, consistent document (the 2.0 text contained contradictions between Section 1 and Section 4)
- AI training for **Closed AI Systems** is prohibited without written consent, training of **Open Models** is allowed; **Assistive Use** (prompting an AI assistant on your own project) stays allowed
- New definitions: Output, Contribution, Assistive Use; contributions are licensed under the base license plus ESOL, contributors keep their attribution
- Two-tier termination: severe violations (4.1 to 4.6) end the license immediately, others (Section 3, 4.7) get a 30-day cure period
- Public documentation (Wall of Shames) only for substantiated violations and, for curable ones, after notice and an opportunity to respond
- Authorization wording no longer contradicts Section 2 and 4.5; defensive security research is expressly possible
- German law references updated and marked informational

See [CHANGELOG.md](./CHANGELOG.md) for details.

</details>

<details>
<summary>How to apply ESOL to your project</summary>

Copy `ESOL_v2.1.md` into your repository root and add this to your `LICENSE` or `README.md`:

```
This Work is licensed under the [INSERT BASE LICENSE, e.g., MIT] together with the
Ethical Security Operations License (ESOL v2.1). Both apply cumulatively.
The ESOL is a mandatory, non-severable condition of use.
By using this software, you agree to all ethical constraints defined in ESOL v2.1.
```

File header identifier: `ESOL-2.1`

Only the copyright holder can apply ESOL to code. You cannot add it to third-party code.

</details>

<details>
<summary>Compatibility with base licenses</summary>

This is a practical overview, not legal advice. ESOL always needs a base license, because it does not replace one.

| Base license family | Combination with ESOL | Notes |
|---|---|---|
| Permissive: MIT, BSD, ISC, Apache 2.0, Zlib, and similar | Works | You may add terms to your own distribution. The result is no longer OSI-"Open Source". |
| Copyleft: GPL, LGPL, AGPL, MPL, EPL, EUPL, CDDL, OSL, and similar | Generally **not** possible for third-party code | These licenses forbid or allow removal of additional restrictions. Only usable for code you own entirely. |
| Creative Commons (BY, SA, NC, ND) | **Not recommended** | CC 4.0 forbids additional terms that restrict the granted rights. CC also advises against use for software. |
| CC0, Unlicense, Public Domain | Only for **your own new or modified parts** | A dedication cannot be re-restricted for the original work. |
| Proprietary / no license | ESOL alone does not grant copy or modify rights | Add a base license that does. |

</details>

---

*Maintained for the community by [@VolkanSah](https://github.com/VolkanSah)* | [Wall of Shames](https://github.com/Wall-of-Shames)
