# Topical Authority — kubikel.co.id

## Role and boundary

`Kubikel.co.id` should be an Indonesian-language reference and commercial decision hub for the ambiguous term **kubikel**. Repository evidence gives the domain three real system families: office/workstation cubicles, toilet cubicles, and electrical cubicles. The site should first help readers identify which system they mean, then route them to material, design, safety, installation, procurement, and maintenance knowledge appropriate to that system.

The domain may cover the same subjects as independently owned `Cubicle.co.id`, `Cubicle.id`, and `Kubikel.id`; cross-domain overlap is allowed and is not cannibalization. On this domain, however, every page needs one clear system and intent. `ToiletCubicle.co.id` and `ToiletPhenolic.co.id` remain useful specialist commercial perspectives, while `Phenolic.id`, `Partisi.co.id`, and future electrical-system properties may publish their own viewpoints. Those domains do not reserve topics away from `Kubikel.co.id`.

Commercial routes on this domain should own consultation, product scope, customization, quotation, fabrication, installation, warranty, and contact intent. Editorial pages should explain decisions and evidence without disguising sales claims as neutral guidance. Project-specific structural, accessibility, electrical, arc-flash, fire, and compliance decisions require competent professionals and current primary requirements.

## Evidence audited

- Canonical repository: `https://github.com/lusmodigital/Kubikel.co.id.git`, branch `main`, audited at commit `eb02302ad3b89d00dd32ca2dd12a89737d3c9b92`.
- Static WordPress/Elementor export: 331 tracked files, including 6 HTML files, 2 XML files, 2 Go maintenance scripts, and 269 JPG/PNG/SVG assets.
- Four meaningful public pages: `/`, `/layanan`, `/tentang-kami`, and `/kontak-kami`. The other two HTML files are plugin cache/backup placeholders, not editorial coverage.
- No article, category, tag, author, pagination, or geography pages were found. Existing article count: 0. Existing location-page count: 0.
- No general page/post sitemap is tracked. `video-sitemap.xml` contains 2 entries for the same `/tentang-kami` URL; one has an empty YouTube ID and both use insecure `http` media URLs.
- Homepage evidence: “Pabrikasi & Pemasangan Kubikel,” custom ordering, nationwide delivery, and three product families: `Cubicle Kantor`, `Cubicle Toilet`, and `Cubicle Listrik`.
- Material evidence: glass (tempered, laminated, and a “ceramic glass” claim requiring clarification), phenolic board, wood/multiplex, and PVC.
- The repository was uploaded in 2023 and last changed in April 2024. Product, standards, contact, operational, and “#1” claims are stale or unverified until rechecked.
- Narrow sparse audit preserved all absent tracked assets; no mass checkout or deletion was used.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Commercial homepage covers all three system families and materials, but makes unverified “#1” and durability claims | expand | Homepage remains commercial overview; KBI-01 and KBI-02 own neutral terminology/selection | Verify current offer, manufacturer/fabricator identity, service area, evidence, and claims |
| `/layanan` | Intended product/service route but most body copy is an unrelated English legal-services template | expand | Commercial service hub; link to KBI-02, KBI-11, KBI-13, and KBI-15 | Replace template copy; verify actual scope, process, warranty, and responsible parties |
| `/tentang-kami` | Company page repeats material summaries and embeds video | expand | Company/evidence route; materials move to KBI-03 hub and children | Verify legal entity, team, facilities, experience, photos, and video ownership |
| `/kontak-kami` | Contact/consultation route | keep | Contact route | Verify email, phone, address, privacy handling, and response process |
| `/family-lawyer-02/` links | Broken legacy home links repeated in header/footer | redirect | `/` | Confirm live behavior, then replace links or add a permanent redirect |
| `http://c/` | Broken placeholder link on electrical-cubicle card | remove | KBI-09 hub or a verified electrical product route | Confirm intended destination before changing |
| `/feed`, `/comments/feed`, `/wp-json/*`, `/?p=*` | WordPress-export references may not exist on static hosting | manual review | Clean static equivalents or remove | Crawl live responses and retain only routes with a purpose |
| `video-sitemap.xml` | Two entries for one page; one empty video ID; insecure media URLs; generated in 2023 | manual review | Valid video sitemap or remove from discovery | Verify actual playable video, thumbnail rights, HTTPS URLs, and sitemap registration |
| Plugin cache/backup HTML | Non-editorial technical placeholders | noindex | Never include in sitemap/navigation | Confirm they cannot surface as indexable URLs |
| Coach/law template assets and copy | Large unrelated legacy footprint weakens trust and maintainability | manual review | Remove only after dependency audit | Build a referenced-asset inventory before cleanup |

## Coverage matrix

| Completeness lens | Topic owners | Coverage decision |
|---|---|---|
| Definition, vocabulary, history, taxonomy | KBI-01, KBI-02 | Explain Indonesian ambiguity before any product recommendation |
| Anatomy, hardware, interfaces, measurements | KBI-04, KBI-05, KBI-11 | Separate components, structural interfaces, and design documents |
| Materials and properties | KBI-03 | Compare evidence by exposure and system; no universal “best” material |
| Mechanisms and science | KBI-05, KBI-08, KBI-10 | Stability, hygiene/moisture, and electrical/thermal protection require distinct disciplines |
| Need, survey, requirements, comparison | KBI-02, KBI-11 | One selection path and one project-definition path |
| Office/workplace lifecycle | KBI-06, KBI-13, KBI-14 | Privacy, acoustics, ergonomics, MEP, reconfiguration, and maintenance |
| Toilet lifecycle | KBI-07, KBI-08, KBI-13, KBI-14 | Layout/accessibility and hygiene/wet-area performance have separate owners |
| Electrical lifecycle | KBI-09, KBI-10, KBI-13, KBI-14 | Education only; design, energization, operation, and return-to-service are specialist work |
| Fabrication, installation, commissioning | KBI-12, KBI-13 | QA evidence is distinct from site execution |
| Inspection, diagnosis, repair, replacement | KBI-14 | Symptom-led paths connect back to materials, structure, hygiene, and electrical safety |
| Budget, procurement, warranty, commercial support | KBI-15 | Comparable scope and evidence, not invented prices or vendor rankings |
| Safety, accessibility, standards, governance | KBI-07, KBI-10, KBI-16 | Current primary sources and competent review are mandatory gates |
| Environment and end-of-life | KBI-17 | Durability, repairability, waste, and embodied impacts without unsupported green claims |
| Geography and climate | KBI-03, KBI-05, KBI-08, KBI-17 | Humidity, wet exposure, corrosion, and logistics change substance; no city-swapped pages |
| Calculators, visuals, checklists, cases | KBI-04, KBI-11–KBI-15 | Use labelled details, survey sheets, acceptance checklists, and genuine documented cases |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| KBI-01 | Kubikel terminology and system boundaries | Identify the intended system before searching, specifying, or buying | kubikel/cubicle; bilik/partisi/workstation; toilet partition; electrical switchgear/enclosure; Indonesian usage; false synonyms; decision vocabulary | Glossary, entity map, terminology examples, expert review | Definitions only; system selection belongs to KBI-02 and detailed families to KBI-06–KBI-10 | 6 |
| KBI-02 | Types, needs, survey, and system selection | Convert a need and site condition into the correct cubicle family | office/toilet/electrical; new build/retrofit; users; exposure; dimensions; privacy; accessibility; load; utilities; budget; when not to use a cubicle | Decision tree, survey form, comparison matrix | Chooses a family; detailed design belongs to KBI-06–KBI-11 | 6 |
| KBI-03 | Materials, finishes, and performance | Select materials from verified properties and exposure rather than labels | compact phenolic/HPL; multiplex/wood; PVC; glass; metal; laminates; moisture; impact; scratches; chemicals; fire claims; corrosion; color; repairability | Property matrix, test-document checklist, material specialist review | Material behavior only; component detailing is KBI-04 and project specification is KBI-11 | 6 |
| KBI-04 | Components, hardware, joints, and tolerances | Read and compare the parts that make a cubicle function | panels; doors; pilasters; frames; feet; hinges; locks; indicators; brackets; channels; seals; edges; fasteners; gaps; tolerances; replaceable parts | Labelled diagrams, hardware matrix, detail drawings | Component anatomy only; structural adequacy belongs to KBI-05 | 6 |
| KBI-05 | Structural stability, substrates, anchors, and movement | Recognize load paths and unsafe support assumptions | lateral load; impact; door load; panel deflection; floor/wall/ceiling support; anchors; hollow substrates; waterproofing penetrations; movement; seismic/site effects; glass support | Load-path diagrams, substrate checklist, structural review | No project-specific sizing or anchor approval; qualified designer/engineer owns calculations | 6 |
| KBI-06 | Office and workstation cubicles | Plan work cubicles around people, tasks, privacy, and building services | workstation types; density; ergonomics; sightlines; acoustics; lighting; power/data; ventilation; accessibility; egress; reconfiguration; cleaning | Layout diagrams, ergonomic checklist, acoustic/MEP review | Office systems only; toilet is KBI-07/KBI-08 and electrical equipment is KBI-09/KBI-10 | 6 |
| KBI-07 | Toilet cubicle planning, privacy, and accessibility | Plan toilet partitions that fit users, circulation, fixtures, and inclusive access | stall layout; door swing; privacy gaps; accessible compartment; ambulant/child/family use; fixture clearances; circulation; emergency access; visual privacy | Plan/section diagrams, accessibility checklist, architect review | Layout and access only; hygiene/material exposure belongs to KBI-08/KBI-03 | 6 |
| KBI-08 | Toilet hygiene, wet-area operation, and durability | Control contamination, moisture, odor, and cleaning damage through the lifecycle | cleanability; joints/gaps; water ingress; floor drainage; ventilation; touchpoints; cleaning chemicals; mold/biofilm; vandalism; inspection; shutdown/escalation | Hygiene zoning diagram, cleaning matrix, facility/health review | No medical or disinfection guarantee; accessibility is KBI-07 and repairs are KBI-14 | 6 |
| KBI-09 | Electrical cubicle fundamentals and configurations | Understand what an electrical cubicle contains and where it sits in a power system | switchgear vs panel/enclosure; LV/MV context; incomer/feeder/coupler; busbar; breaker; metering; protection/control; compartments; cable entry; single-line relationship | Anatomy diagram, simplified single-line, electrical-engineer review | Education only; protection ratings and hazards belong to KBI-10 | 6 |
| KBI-10 | Electrical enclosure, thermal, arc, fire, and ingress safety | Ask the right safety/performance questions without treating a rating as total protection | IP rating; internal separation; thermal rise; ventilation; short-circuit withstand; arc fault/internal arc; fire/smoke; earthing/bonding; interlocks; labels; access; environmental conditions | Protection-layer diagram, rating checklist, current primary standards, electrical/fire review | No design, energization, work instruction, or arc-flash calculation; competent electrical professionals own them | 6 |
| KBI-11 | Measurement, design, drawings, and specification | Produce a coordinated information package before fabrication | site measurement; room/grid; equipment envelope; module schedule; clearances; elevations; details; hardware schedule; electrical data; interfaces; revisions; approval | Survey sheet, drawing set index, design RACI | Defines information and coordination; fabrication belongs to KBI-12 and installation to KBI-13 | 6 |
| KBI-12 | Fabrication, quality assurance, and traceability | Verify that manufactured parts match approved scope | cutting/forming; edge finishing; drilling; bonding/welding; glass processing; panel conditioning; tolerances; trial assembly; identification; certificates; inspection/test plan; nonconformance | Process map, ITP template, sample records, fabrication expert review | Factory/preassembly evidence only; site acceptance belongs to KBI-13 | 6 |
| KBI-13 | Logistics, installation, commissioning, and handover | Coordinate safe delivery-to-use without damaging systems or buildings | packaging; transport; storage; access; sequencing; substrate readiness; setting out; anchors; waterproofing; MEP isolation; electrical tests; snagging; cleaning; as-builts; training | Method flow, readiness checklist, commissioning matrix, specialist review | Planning guidance only; approved method statements and competent installers govern execution | 6 |
| KBI-14 | Inspection, maintenance, defects, repair, and replacement | Diagnose symptom categories and choose safe escalation paths | loose doors; failed locks; swelling/delamination; cracked glass; corrosion; movement; water ingress; odor/mold; vandalism; electrical hot spots/noise/trips; records; repair vs replace | Defect atlas, diagnostic tree, maintenance matrix | Does not declare structural/electrical safety or return equipment to service; specialists own clearance | 6 |
| KBI-15 | Procurement, quotation, contracts, warranty, and acceptance | Compare offers on equal scope and retain useful evidence | BOQ; drawings; alternates; exclusions; samples; lead time; logistics; installation; tests; warranty; spares; payment; change control; acceptance; supplier verification | Bid matrix, document checklist, contract-scope review | No price promises, vendor rankings, or legal advice; KBI-11 owns technical requirements | 6 |
| KBI-16 | K3, public safety, standards, and professional roles | Identify high-consequence hazards, current authorities, and decision owners | sharp/heavy panels; glass; drilling; silica/dust/chemicals; work at height; occupied toilets/offices; electrical isolation/LOTO; arc/fire; accessibility; permits; SNI/IEC/ISO/manufacturer rules; sign-off | Hazard map, stop-work checklist, institution map, current primary sources, K3/professional review | Preparedness only; site procedures, legal interpretation, and compliance approval remain with authorities/competent persons | 6 |
| KBI-17 | Lifecycle, environment, adaptability, and end-of-life | Compare whole-life value without unsupported sustainability claims | service life; cleaning/maintenance burden; modularity; repair; reuse; material separation; recycled content claims; VOC/indoor air; energy impacts; waste; take-back; decommissioning | Lifecycle matrix, sourced comparison, environmental review | No project LCA or green certification claim; procurement decisions belong to KBI-15 | 6 |

## Related-domain opportunities

| Domain | Independent viewpoint | Collaboration opportunity |
|---|---|---|
| `Cubicle.co.id`, `Cubicle.id`, `Kubikel.id` | Separate owned editorial properties for cubicle/kubikel systems | Compare query language and reader behavior; reuse evidence methods, not text or page templates |
| `ToiletCubicle.co.id` | Toilet-cubicle commercial specialist | Link only when useful to buyers; `Kubikel.co.id` keeps neutral layout, hygiene, and material education |
| `ToiletPhenolic.co.id`, `Phenolic.id` | Phenolic toilet application and phenolic material science | Cross-domain research on test documents, cleaning compatibility, durability, and fabrication |
| `Partisi.co.id`, `PartisiRuangan.co.id` | Broader interior partition systems | Coordinate office partition/workstation distinctions without suppressing either domain |
| `Kaca.co.id`, `KacaTempered.co.id`, `Kayu.co.id`, `Almini.id` | Material-specific expertise | Commission verified property/detail references and specialist review |
| `Safety.co.id`, `FireSafety.co.id` | Safety and fire-system perspectives | Review K3/fire claims; do not imply those domains certify this site |

## Consolidation plan

1. Preserve the four meaningful routes while rewriting `/layanan` and strengthening evidence on `/` and `/tentang-kami`.
2. Fix `/family-lawyer-02/` and `http://c/` before publishing articles; crawl static WordPress endpoints and remove dead discovery links.
3. Rebuild sitemap discovery from actual canonical routes. Repair or remove the invalid duplicate video entry.
4. Keep product/service intent on commercial routes. New editorial hubs use the catalog slugs and link contextually to `/layanan` or `/kontak-kami`.
5. Do not create geographic variants. Climate, humidity, coastal exposure, logistics, or regulation belong inside substantive system pages unless original local evidence justifies a case study.
6. Audit asset dependencies before deleting unrelated coach/law media or plugin artifacts.

## Internal-link architecture

- `/` introduces the three meanings and links to KBI-01, KBI-02, KBI-06, KBI-07, and KBI-09.
- KBI-01 routes readers to the correct family; KBI-02 routes projects to requirements, materials, design, procurement, and commercial consultation.
- KBI-06, KBI-07/KBI-08, and KBI-09/KBI-10 are separate system clusters. Shared KBI-03–KBI-05 and KBI-11–KBI-17 pages link back only where interfaces are real.
- Diagnostic pages in KBI-14 link to prevention/detail pages, repair-vs-replacement decisions, and safety stop conditions.
- Procurement pages link to technical requirements, QA, commissioning, and warranty evidence before `/layanan` or `/kontak-kami`.
- Every article links to its parent hub; each hub lists all six children. Related IDs in `ARTICLE_CATALOG.md` define the first lateral links.

## Evidence and editorial standards

- Write in clear Indonesian; define necessary English technical terms once.
- Never invent prices, tests, certificates, ratings, standard clauses, project experience, case results, or “best/#1” claims.
- Use current primary standards, laws, regulator/utility guidance, and manufacturer documents. Record edition/date and applicability; require expert review before publishing safety-critical material.
- Toilet accessibility and hygiene content requires architect/accessibility and facility/hygiene review. Electrical content requires a qualified electrical engineer; arc/fire claims additionally require relevant protection/fire expertise.
- Illustrations are conceptual unless based on an approved project. State dimensions only when sourced and applicable.
- Separate verified fact, observed site evidence, editorial hypothesis, and commercial claim.
- Original photos/cases require provenance, permission, date, system type, conditions, and limitations.

## First bounded publication cluster

Publish 12 assets: KBI-01-01, KBI-01-02, KBI-02-01, KBI-02-02, KBI-03-01, KBI-04-01, KBI-06-01, KBI-07-01, KBI-08-01, KBI-09-01, KBI-10-01, and KBI-15-01.

This cluster first resolves the ambiguous term, then gives one entry point for each system family plus shared material/component and procurement decisions. Link the central terminology guide to every family, link each family back to selection and relevant safety pages, and link procurement to requirements and evidence.

Monitor indexation, impressions by intent/system family, clicks from terminology to family pages, checklist/diagram engagement, qualified enquiries by stated system, response/conversion/collected-income outcomes, and Search Console query/page overlap. Expand only after the first cluster is reviewed, indexed, internally connected, and producing useful reader or commercial signals.

## Definition of done

- All 17 topics have six distinct briefs and pass the shared validator.
- Proposed IDs, titles, and slugs are unique and do not collide with existing routes.
- Same-domain overlap follows the anti-cannibalization register; no city/province/region swaps exist.
- Broken legacy navigation and invalid sitemap discovery are resolved before article publication.
- High-stakes structural, accessibility, hygiene, electrical, arc/fire, K3, and standards content receives the stated evidence and expert review.
- The first cluster is published with hub links, valid metadata/canonicals/sitemap entries, baseline analytics, enquiry attribution, and a stop/continue review.
