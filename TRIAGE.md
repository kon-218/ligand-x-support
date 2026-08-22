# Public triage workflow

The public issue is the customer-visible record even when implementation work occurs in a private
repository. Maintainers should update it at meaningful transitions without exposing private source,
security details, customer information, or internal credentials.

## Status lifecycle

| Label | Meaning |
|---|---|
| `status: needs-triage` | Submitted and awaiting classification. |
| `status: needs-info` | More information is required from the reporter. |
| `status: confirmed` | Reproduced or otherwise accepted as a valid issue. |
| `status: planned` | Accepted into the product plan, but work has not started. |
| `status: in-progress` | Implementation or investigation is actively underway. |
| `status: blocked` | Progress depends on an identified external condition. |
| `status: ready-for-release` | A change is complete but not in a stable release. |
| `status: released` | The resolution is available in a named release. |

Status labels are mutually exclusive. Replace the previous status whenever the issue moves. A milestone
communicates a target release, not a guarantee.

## Maintainer checklist

1. Confirm no sensitive data or uncoordinated vulnerability details are exposed.
2. Normalize the title and apply exactly one type, one product, and one status label.
3. Add module, platform, and impact labels supported by the report.
4. Search for duplicates and link both directions before closing a duplicate.
5. Reproduce or request the minimum missing evidence.
6. Keep public status current while any private implementation ticket is active.
7. When released, state the first version containing the fix and provide release or documentation links.

`impact: critical` is reserved for maintainers and indicates widespread loss of a core product function,
data-integrity risk, or an urgent production regression. Security severity is never triaged publicly.

