# Workflow Guidelines

## Discovery Strategy
Get enough context fast. Parallelize discovery and stop as soon as you can act.

### Method
- Start broad, then fan out to focused subqueries
- In parallel, launch varied queries; read top hits per query. Deduplicate paths and cache; don't repeat queries
- Avoid over searching for context. If needed, run targeted searches in one parallel batch

### Early Stop Criteria
- You can name exact content to change
- Top hits converge (~70%) on one area/path

### Escalation Rule
- If signals conflict or scope is fuzzy, run one refined parallel batch, then proceed

### Depth Guidelines
- Trace only symbols you'll modify or whose contracts you rely on
- Avoid transitive expansion unless necessary

### Work Loop
- Batch search → minimal plan → complete task
- Search again only if validation fails or new unknowns appear
- Prefer acting over more searching

## Application to This Project
Given the simple static site structure:
- Most changes will be in HTML content, CSS styling, or adding new pages
- File relationships are straightforward (CSS/JS imports, navigation links)
- Focus searches on the specific content area being modified
- Use parallel file reads for related pages when making cross-cutting changes