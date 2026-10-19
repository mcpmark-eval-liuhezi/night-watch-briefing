# The Night Watch — Podcast Research Pack

Compiled from live sources for the upcoming episode on Rembrandt's *The Night Watch* (Rijksmuseum). All data below was pulled directly from the Rijksmuseum collection API and web sources on the day of compilation — nothing from memory.

---

## 1. Museum Record

Confirmed via the Rijksmuseum collection record for the object.

- **Object number:** SK-C-5 (confirmed — this is the object number under which the work is catalogued)
- **Title (as recorded by the museum's collection data):** *Het korporaalschap van kapitein Frans Banninck Cocq en luitenant Willem van Ruytenburch, bekend als de 'Nachtwacht'*
- **English title on the collection page:** The Night Watch — Militia Company of District II under the Command of Captain Frans Banninck Cocq
- **Year the record dates it to:** 1642 (record date field: 1642-01-01)
- **Maker:** Rembrandt van Rijn
- **Permanent link (museum):** https://www.rijksmuseum.nl/en/collection/SK-C-5
- **Linked Art / record ID:** https://id.rijksmuseum.nl/200107928
- **Display status:** on display in the Night Watch Gallery
- **Materials / technique (from collection page):** oil on canvas
- **Dimensions (from collection page):** height 379.5 cm x width 453.5 cm x weight 337 kg x weight 170 kg

---

## 2. Career Timeline Span

A chronological sample of 20 works by Rembrandt van Rijn held in the Rijksmuseum collection, as returned by the collection API.

**Earliest dated work in the sample:** *Allegorisch musicerend gezelschap* (SK-A-4674) — **1626**. Two other 1626 works also appear in the sample: *Tobit beschuldigt Anna van het stelen van een bokje* (SK-A-4717) and one record listed by object number only (SK-A-4096).

**Latest dated work in the sample:** *Portrait of a couple as figures from the Old Testament, known as 'The Jewish bride'* (SK-C-216) — **1665**.

### Full chronological sample (20 works)

| # | Year | Object number | Title |
|---|------|---------------|-------|
| 1 | 1626 | SK-A-4674 | Allegorisch musicerend gezelschap |
| 2 | 1626 | SK-A-4717 | Tobit beschuldigt Anna van het stelen van een bokje |
| 3 | 1626 | SK-A-4096 | (title not returned in sample data) |
| 4 | 1628 | SK-A-4691 | Self-Portrait at an Early Age |
| 5 | 1628 | RP-T-1961-75 | (title not returned in sample data) |
| 6 | 1629 | RP-T-1889-A-2046(R) | (title not returned in sample data) |
| 7 | 1630 | SK-A-3276 | (title not returned in sample data) |
| 8 | 1631 | SK-A-3066 | An old woman, probably Rembrandt's mother, Neeltgen Willemsdr van Zuydtbroeck (d 1640), apparently in the guise of the prophetess Anna |
| 9 | 1633 | SK-A-4057 | Portrait of a Woman, thought to be Rembrandt's Wife Saskia van Uylenburgh (1612-1642) |
| 10 | 1634 | SK-A-4833 | Portrait of Haesje Jacobsdr van Cleyburg (1583-1641). Wife of the Rotterdam Brewer Dirck Jansz Pesser (1586-1651) |
| 11 | 1635 | SK-A-3340 | An oriental |
| 12 | 1638 | SK-A-1935 | De stenen brug |
| 13 | 1639 | SK-A-3981 | (title not returned in sample data) |
| 14 | 1639 | SK-C-597 | Portrait of a woman, probably Maria Trip |
| 15 | 1642 | SK-C-5 | Het korporaalschap van kapitein Frans Banninck Cocq en luitenant Willem van Ruytenburch, bekend als de 'Nachtwacht' (The Night Watch) |
| 16 | 1660 | SK-A-3137 | De verloochening van Petrus |
| 17 | 1660 | SK-A-3138 | Rembrandt's son in a monk's habit, possibly in the guise of St Francis of Assisi |
| 18 | 1661 | SK-A-4050 | (title not returned in sample data) |
| 19 | 1662 | SK-C-6 | De Staalmeesters: het college van staalmeesters (waardijns) van het Amsterdamse lakenbereidersgilde (The Syndics) |
| 20 | 1665 | SK-C-216 | Portrait of a couple as figures from the Old Testament, known as 'The Jewish bride' |

Span of the sample: **1626 – 1665**, with *The Night Watch* (1642) sitting at the midpoint of Rembrandt's career represented in this collection.

---

## 3. Other Works by Rembrandt in the Collection

**Search by maker:** a collection search for **Rembrandt van Rijn** returned **1,437 total results**.

Twelve of those works (other than The Night Watch) with object numbers and titles:

| Object number | Title | Date |
|---------------|-------|------|
| SK-A-1935 | De stenen brug | 1638 |
| SK-C-6 | De Staalmeesters: het college van staalmeesters (waardijns) van het Amsterdamse lakenbereidersgilde | 1662 |
| SK-A-3340 | An oriental | 1635 |
| SK-A-3981 | (title not returned in search data) | 1639 |
| SK-A-3137 | De verloochening van Petrus | 1660 |
| SK-C-216 | Portrait of a couple as figures from the Old Testament, known as 'The Jewish bride' | 1665 |
| SK-A-4674 | Allegorisch musicerend gezelschap | 1626 |
| SK-A-4833 | Portrait of Haesje Jacobsdr van Cleyburg (1583-1641). Wife of the Rotterdam Brewer Dirck Jansz Pesser (1586-1651) | 1634 |
| SK-A-3138 | Rembrandt's son in a monk's habit, possibly in the guise of St Francis of Assisi | 1660 |
| SK-A-4691 | Self-Portrait at an Early Age | 1628 |
| SK-C-597 | Portrait of a woman, probably Maria Trip | 1639 |
| SK-A-4057 | Portrait of a Woman, thought to be Rembrandt's Wife Saskia van Uylenburgh (1612-1642) | 1633 |

### Spot-checks — three individual records pulled and compared

The individual record API returns Linked Art structured data with rich keys (dimensions, materials via `made_of`, classification, attribution, current location, etc.). Notes on what the individual records add:

**1. SK-C-6 — De Staalmeesters (The Syndics), dated 1662**
- Individual record confirms object number SK-C-6 and the full Dutch title as above.
- The record's structured data includes a `dimension` block and a `made_of` block, i.e. materials and physical dimensions are attached to this record (the list-level search does not expose them).
- Dating confirmed as 1662.

**2. SK-C-216 — The Jewish Bride, dated 1665**
- Individual record confirms object number SK-C-216, the English title "Portrait of a couple as figures from the Old Testament, known as 'The Jewish bride'", and the 1665 date.
- Record carries `dimension` and `made_of` fields plus attribution/provenance-style blocks (`assigned_by`, `attributed_by`, `produced_by`, `current_location`) that go beyond the list view.
- Note: the public collection page dates this work c. 1665 – c. 1669, slightly later than the flat 1665 in the API record — worth flagging if quoted on air.

**3. SK-A-4057 — Portrait of Saskia van Uylenburgh, dated 1633**
- Individual record confirms object number SK-A-4057, the full title "Portrait of a Woman, thought to be Rembrandt's Wife Saskia van Uylenburgh (1612-1642)", and the 1633 date.
- This record additionally includes a `current_location` field (present in this record but not in the other two spot-checks), indicating a specific display location for the work.
- Dating confirmed as 1633.

**General note on the spot-checks:** the individual records carry structured fields the search list does not — most notably materials (`made_of`), dimensions (`dimension`), attribution (`assigned_by`, `attributed_by`, `produced_by`), classification and `current_location`. Where titles appear missing in the list (e.g. SK-A-3981, SK-A-3276), the individual records are the place to retrieve them.

---

## 4. Web Fact-Check

Two angles checked against live web sources.

### Completion year double-check

The Google search results and the Rijksmuseum's own collection page both confirm the completion date of **1642**. A ResearchGate result describes the work as "The Night Watch (1642, oil on canvas, h 378 ...)", consistent with the museum's 379.5 cm height figure (the ResearchGate snippet truncates at "h 378..."). The Rijksmuseum collection page states plainly: "Rembrandt van Rijn, 1642."

### Current angle: Operation Night Watch (research & restoration)

**Source read:** Rijksmuseum press release, "RESTORATION BEGINS OF REMBRANDT'S THE NIGHT WATCH," published 12 November 2024 — https://www.rijksmuseum.nl/en/press/press-releases/restoration-begins-of-rembrandt-s-the-night-watch

Concrete details pulled from that page:

1. **Team and timing:** Following five years of intensive research and the re-stretching of the painting, a team of **eight Rijksmuseum conservators** started removing the varnish from The Night Watch — this marked the beginning of the **second phase of Operation Night Watch**, described as the biggest ever research and restoration project devoted to the masterpiece.
2. **Technique:** Conservators use a special tissue prepared with a solvent, placed against the painting's surface for a short, limited time so the varnish is solubilised and absorbed into the tissue; any remnants of even older varnish are then removed with cotton swabs under a microscope. The varnish layers being removed were applied as part of the painting's restoration in **1975-1976**.
3. **Public viewing:** Visitors can follow the restoration live in the Night Watch Gallery, where the work is carried out with microscopic precision in a see-through glass chamber. The page quotes **Taco Dibbits, Director of the Rijksmuseum**.

Supporting details from the museum's Operation Night Watch story page (https://www.rijksmuseum.nl/en/stories/operation-night-watch) and from the search results:

- The research involved digital imaging, scientific and technical studies, computer science and artificial intelligence, with collaborators including AkzoNobel (main partner), the Cultural Heritage Agency of the Netherlands (RCE), TU Delft, University of Amsterdam, Amsterdam UMC, University of Antwerp, VU Amsterdam, TU Eindhoven and the National Gallery of Art, Washington DC.
- A key earlier finding from the research phase (via the museum's "initial results" page): mapping of chemical elements revealed that **Rembrandt first painted feathers into the picture but later removed them**.

---

## Sources

- Rijksmuseum collection record for SK-C-5 (API): https://id.rijksmuseum.nl/200107928 and https://www.rijksmuseum.nl/en/collection/SK-C-5
- Rijksmuseum collection search and artist timeline data (Rijksmuseum Data Services)
- Rijksmuseum press release (12 Nov 2024): https://www.rijksmuseum.nl/en/press/press-releases/restoration-begins-of-rembrandt-s-the-night-watch
- Rijksmuseum Operation Night Watch story page: https://www.rijksmuseum.nl/en/stories/operation-night-watch
- Google web search (via SERP) and DuckDuckGo web search for cross-referencing
