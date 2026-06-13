# Golfregler og definisjoner – RAG-optimalisert

Norske golfregler og definisjoner strukturert for bruk i RAG-systemer (Retrieval-Augmented Generation).

## Innhold

### Regler (`/Regler`)

Offisielle golfregler (R&A 2023) delt inn i enkeltfiler per regel eller regelavsnitt. Hver fil dekker én avgrenset del av reglene og er utformet for å gi presise, kontekstriktige svar på regelspørsmål.

### Definisjoner (`/Definisjoner`)

Offisielle definisjoner fra R&A-regelverket, én fil per definisjon eller tett beslektede definisjonsgruppe. Totalt 42 filer som dekker alle 73 offisielle definisjoner.

## Filformat

Hver fil inneholder:

- **YAML-frontmatter** med metadata (`doc_type`, `language`, `source_type`, `retrieval_priority` m.m.)
- **Kort sammendrag** for søk
- **Søkeord** på norsk og engelsk
- **Vanlige spørsmål** fra golfere
- **Relaterte regler** med regelreferanser
- **Offisiell tekst** bevart ordrett fra R&A-regelverket

## Språk

Norsk bokmål (`nb`). Søkeord inkluderer både norske og engelske termer for bred søkedekning.

## Kilde

R&A – offisielle golfregler 2023. Tekstinnholdet er hentet direkte fra det norske regelverket uten endringer.

## Bruksområde

Beregnet for bruk som kunnskapsbase i AI-assistenter og RAG-pipelines for golfregel-spørsmål.
