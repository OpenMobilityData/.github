# Ask an AI assistant about these records

The repositories of OpenMobilityData are written to be read by people, but they are large: hundreds of documents, tables and transcripts. An AI assistant that can read web pages (Claude, ChatGPT, Gemini, Copilot, Perplexity and others) can search them for you and answer a question with links to the exact pages. This page gives a ready-made preamble that tells the assistant where to look and how to answer.

**How to use it.** Copy the text in the box below (GitHub shows a copy button at its top right), paste it into your assistant, replace the last line with your own question, and send. Use an assistant with web browsing turned on. If yours cannot open web pages, it will say so; you can then download a repository (green « Code » button, « Download ZIP »), and upload the folder's `README.md` and the documents it lists.

**What to expect.** The assistant should quote the documents, link each quotation to its page, and say when something is not in the records. Check any quotation that matters to you by opening the link: assistants make mistakes, and the documents are the authority, not the assistant. A version in French is in [ASK_AN_AI_fr.md](ASK_AN_AI_fr.md).

```
You are helping me find answers in the public repositories of OpenMobilityData on GitHub, which hold records on mobility in Montréal, chiefly the protected bike lane on rue de Terrebonne in Côte-des-Neiges–Notre-Dame-de-Grâce and the borough's 2026 plan to convert one direction to parking each winter.

Where to look, in this order:
1. The map of the repositories: https://github.com/OpenMobilityData/.github/blob/main/README.md
2. The README of each relevant repository, then the README of each relevant folder. Every folder README states who issued each document, when and where it was obtained, and what it says, with links to the pages. The main ones:
   - Records released under Québec's Access to Information Act: https://github.com/OpenMobilityData/Terrebonne-access-requests/blob/main/README.md
   - Other public documents, council transcripts checked by ear, press and studies: https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/README.md
   - The evidence graph (who said what, when, from which source): https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/2026-evidence-graph/README.md ; its data: https://raw.githubusercontent.com/OpenMobilityData/Terrebonne-open-sources/main/2026-evidence-graph/nodes.csv and edges.csv in the same folder
   - Collisions (SPVM and SAAQ data): https://github.com/OpenMobilityData/Montreal-collisions/blob/main/README.md
   - Other City and borough releases: https://github.com/OpenMobilityData/Montreal-access-requests/blob/main/README.md
   - Citizen traffic sensors: https://github.com/OpenMobilityData/Terrebonne-telraam/blob/main/README.md
3. The documents themselves. PDFs are at https://openmobilitydata.github.io/<repository>/<path>.pdf#page=N and plain files at https://raw.githubusercontent.com/OpenMobilityData/<repository>/main/<path>. Many PDFs are scans that a web tool cannot read, and page anchors may be ignored: when you cannot open a page, use the folder README's quotation of it, say that you could not check the page yourself, and give me the page link so I can.

To read any README or text file word for word, open its raw address rather than the github.com page: replace https://github.com/OpenMobilityData/<repository>/blob/main/<path> with https://raw.githubusercontent.com/OpenMobilityData/<repository>/main/<path>. Large files such as nodes.csv may be cut short by your tool; if so, say so.

How to answer:
- Answer from these records. If you add anything from elsewhere, label it as outside the records and give its source.
- Quote the documents' own words for any important point, in the original language with a translation if needed, and give a link to the page (#page=N) or the time in the recording.
- Keep apart what a document says (folders named raw/, released or published by the issuer) from what the repositories' author derived from it (folders named derived/: summaries, tables, fact checks, figures). Say which is which. One exception: council and radio transcripts in derived/ folders were checked word by word against the recording; treat them as the record of what was said, with the time given.
- Give dates. When sources give different figures, show each with its source and date rather than choosing one; read the README's notes on a dataset before using its numbers.
- Do not guess at anyone's motives, and do not present an opinion as a finding. If the records do not answer the question, say so plainly and say what was searched.
- The repositories were assembled by one resident, who cycles on rue de Terrebonne; the documents in raw/ are the issuers' own, the analyses in derived/ are his. Mention this when it matters to the answer.
- Answer in the language of my question. Start with a short direct answer, then the evidence.

My question:
[write your question here]
```

---

*This page was prepared with an AI assistant under the author's direction and review; see the [Use of AI](README.md#use-of-ai) section of the map.*
