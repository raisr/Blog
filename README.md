# Technische Knowledge Base

Dieses Repository ist eine persönliche technische Wissenssammlung.
Es handelt sich **nicht um einen Blog** im herkömmlichen Sinne,
sondern um eine versionierte Sammlung von Artikeln, Notizen und Erkenntnissen aus der Praxis.

Der Fokus liegt auf **Softwareentwicklung, Architektur und Infrastruktur**.
Inhalte entstehen iterativ – von ersten Ideen bis zu ausgearbeiteten Artikeln –
ausschließlich mit den Bordmitteln von GitHub.

---

## 📚 Artikel

Fertige Artikel liegen als Markdown-Dateien im Repository und sind hier kuratiert verlinkt.

---

## 🔍 Thematische Suche (über Issues)

Zur inhaltlichen Erschließung werden GitHub Issues als Metadaten- und Suchlayer verwendet.
Labels fungieren dabei als Themen-Tags.

- [Alle veröffentlichten Artikel](../../issues?q=is%3Aissue+label%3Astatus%3Apublished)
- [Alle unveröffentlichten Artikel](../../issues?q=is%3Aissue%20-label%3Astatus%3Apublished)

Jedes veröffentlichte Issue verweist auf den zugehörigen Markdown-Artikel.

---

## 🧠 Arbeitsweise / Workflow

Der typische Ablauf eines Artikels:

1. **Idee**
   - Ein Artikel beginnt als Issue (`status:idea`)
   - Motivation, grobe Struktur und Notizen werden gesammelt

2. **Ausarbeitung**
   - Der Inhalt wird schrittweise konkretisiert (`status:wip`)
   - Der eigentliche Artikel entsteht als Markdown-Datei unter `drafts/`

3. **Veröffentlicht**
   - Der Artikel ist abgeschlossen und verlinkt (`status:published`)
   - Das Issue dient als Metadaten- und Einstiegspunkt
   - Der Artikel wird in `articles/year/` verschoben 

Issues bleiben bewusst erhalten, um Kontext, Historie und Gedankengänge nachvollziehbar zu machen.

---

## 🗂 Repository-Struktur

```text
Blog/
│
├─ articles/
│   └─ year/
│       ├─ 2025
│       │   ├─ 2025-02-10-article-01.md
│       │   └─ ...
│       └─ ...
│
├─ drafts/
│   ├─ 2025-02-10-article-01.draft.md
│   └─ ...
│
├─ assets/
│   └─ images/
│
└─ README.md

