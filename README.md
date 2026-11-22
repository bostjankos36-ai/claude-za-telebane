# 🤖 Claude Code za telebane

Najpreprostejši vodnik za delo s **Claude Code** — v slovenščini, brez nepotrebne navlake.

> Ideja: namesto da Claudu vsakič vse razlagaš od začetka, mu pustiš v projektu nekaj datotek z navodili. Potem dela bolje in hitreje.

---

## 📁 Kaj je v tem repozitoriju

```
claude-za-telebane/
├── README.md                  ← ta vodnik
├── CLAUDE.md                  ← "pravila hiše" za Clauda
└── .claude/
    ├── commands/
    │   └── razlozi.md         ← ukaz /razlozi
    ├── agents/
    │   └── pregledovalec.md   ← pomočnik, ki pregleda kodo
    └── skills/
        └── preveri-kodo/
            └── SKILL.md       ← veščina za preverjanje
```

Vse datoteke so navadno besedilo (Markdown). Lahko jih kopiraš v svoj projekt in prilagodiš.

---

## 🧱 4 osnovni gradniki

| Gradnik | Kje je | Čemu služi |
|---|---|---|
| **CLAUDE.md** | koren projekta | Pravila, ki jih Claude prebere **vedno**. Kot listek na hladilniku. |
| **Ukazi** | `.claude/commands/` | Bližnjice. Napišeš `/razlozi` namesto dolgega navodila. |
| **Podagenti** | `.claude/agents/` | Pomočniki z eno nalogo (npr. samo pregled kode). |
| **Veščine** | `.claude/skills/ime/SKILL.md` | Recepti, ki jih Claude uporabi sam, ko so potrebni. |

---

## ✅ 10 nasvetov za telebane

1. **Najprej načrt, potem koda.** Reci: *"Najprej mi napiši načrt, ne spreminjaj še ničesar."*
2. **Ena naloga naenkrat.** Majhne prošnje = manj napak.
3. **Bodi konkreten.** Ne *"popravi stran"*, ampak *"gumb Shrani ne dela na telefonu"*.
4. **Pokaži primer.** Slika zaslona ali primer pove več kot opis.
5. **CLAUDE.md naj bo kratek.** Samo pravila, ki res veljajo vedno.
6. **Ko se ponavljaš → naredi ukaz.** Če isto prosiš 3-krat, to sodi v `.claude/commands/`.
7. **Preveri, ne zaupaj na slepo.** Reci: *"Preizkusi, ali dela, in mi pokaži."*
8. **Shranjuj pogosto (commit).** Tako se lahko vedno vrneš nazaj.
9. **Ko se zaplete → nov pogovor.** Predolg pogovor zmede tudi Clauda.
10. **Ne razumeš? Vprašaj.** Uporabi ukaz `/razlozi`. Ni neumnih vprašanj.

---

## 🚀 Kako začeti (3 koraki)

1. Kopiraj datoteko `CLAUDE.md` in mapo `.claude/` v svoj projekt.
2. V `CLAUDE.md` popravi opis projekta in svoja pravila.
3. Odpri Claude Code v tem projektu in napiši na primer: `/razlozi index.html`

To je vse. 🎉

---

## 📚 Navdih

Po vzoru odprtokodnega vodnika [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) — tukaj v zelo poenostavljeni, slovenski obliki.
