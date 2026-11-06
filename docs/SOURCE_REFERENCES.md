# Source reference updates

Updated 6 November 2026. These corrections identify sources and translation authorship. They do not mark any document as human-verified or confirm that an older customary text is still in force.

## Canggu awig-awig

The team supplied https://jidhat.baliprov.go.id/awig-awig/detail/212 as the origin of the Balinese scan and confirmed that the Indonesian translation was prepared by the Mawacara AI team. The source URL and translator credit replace the previous unknown-origin metadata. The 2012 edition and unofficial-translation caveats remain. Indonesian excerpts are labelled as translations rather than original Balinese wording.

## Foreign-tourist circular

The old Dinas Pariwisata PDF URL returned HTTP 404 on 6 November 2026. For records that selected it as their primary link, the application now links to the official provincial government publication explaining Circular 7/2025:

https://bmc.baliprov.go.id/news/title/tertibkan-turis-asing-yang-berulah-di-bali-gubernur-koster-keluarkan-se-nomor-7-tahun-2025

This is an official news explanation, not the circular PDF itself. Research summaries remain GENERAL_ADVISORY and UNVERIFIED. The original PDF URL remains in the source-reference list for provenance.

The Denpasar transport article about sidewalks and the Bali prosecutor's Foreigner Legal Service page were accessible and their content was checked. Their primary-link-unavailable flags were removed without changing the summaries or treating them as Canggu-specific regulations.

## Rebuilding metadata

`knowledge/source_overrides.json` records the corrected reference URLs. Stage 1 applies it before writing the source inventory and extracted-document headers. Stage 2 assigns unknown-link or inaccessible-primary-link flags only where applicable. Current generated document, unit, and chunk metadata has been updated with the same corrections.

Document text, chunk boundaries, embedding vectors, verification status, and applicability remain unchanged. Only metadata changed, so the stage-4 manifest's chunk-file hash is refreshed without re-embedding text.
