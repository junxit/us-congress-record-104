# What this repository does not hold — 104th Congress

The 104th Congress sat from 1995-01-03 to 1997-01-02.

## Coverage

| Edition | Branch | Issue days | Documents | First | Last |
|---|---|---|---|---|---|
| Daily edition (CREC) | `daily` | 357 | 52,658 | 1995-01-04 | 1996-10-21 |
| Bound edition (CRECB) | `bound` | 0 | 0 | — | — |

Every figure above is read back out of the branch itself, not counted by
the run that wrote it — so this table describes the repository as it
stands, and a re-run that finds everything already built renders it
identically and commits nothing.

## Issue days with no readable document

45 issue day(s) were listed upstream and every granule in them
failed to produce text, so they have no commit at all.

## Granules with no text

1,314 granule(s) are listed in their issue and have no
readable HTML rendition, so the issue's index skips a number where each
one should be. Ordinals are assigned over every listed granule
precisely so the hole stays visible rather than being closed up.

The complete list is in [`GAPS.tsv`](GAPS.tsv), which is
tab-separated so it can be grepped and diffed without a Markdown
reader. The first few:

- `GPO-CRECB-1995-pt1-1`
- `GPO-CRECB-1995-pt1-1-1`
- `GPO-CRECB-1995-pt1-1-2`
- `GPO-CRECB-1995-pt1-1-3`
- `GPO-CRECB-1995-pt1-2`
- `GPO-CRECB-1995-pt1-2-1`
- `GPO-CRECB-1995-pt1-2-2`
- `GPO-CRECB-1995-pt1-2-3`
- `GPO-CRECB-1995-pt1-3`
- `GPO-CRECB-1995-pt1-3-1`
- `GPO-CRECB-1995-pt1-4`
- `GPO-CRECB-1995-pt1-4-1`
- `GPO-CRECB-1995-pt1-4-2`
- `GPO-CRECB-1995-pt1-4-3`
- `GPO-CRECB-1995-pt1-5`
- `GPO-CRECB-1995-pt1-5-1`
- `GPO-CRECB-1995-pt1-6`
- `GPO-CRECB-1995-pt1-6-1`
- `GPO-CRECB-1995-pt1-6-2`
- `GPO-CRECB-1995-pt1-6-3`
- `GPO-CRECB-1995-pt1-7`
- `GPO-CRECB-1995-pt1-7-1`
- `GPO-CRECB-1995-pt1-8`
- `GPO-CRECB-1995-pt1-8-1`
- `GPO-CRECB-1995-pt1-8-2`
- `GPO-CRECB-1995-pt1-8-3`
- `GPO-CRECB-1995-pt1-9`
- `GPO-CRECB-1995-pt1-9-1`
- `GPO-CRECB-1995-pt1-9-2`
- `GPO-CRECB-1995-pt1-9-3`
- `GPO-CRECB-1995-pt10-1`
- `GPO-CRECB-1995-pt10-1-1`
- `GPO-CRECB-1995-pt10-1-2`
- `GPO-CRECB-1995-pt10-1-3`
- `GPO-CRECB-1995-pt10-2`
- `GPO-CRECB-1995-pt10-2-1`
- `GPO-CRECB-1995-pt10-3`
- `GPO-CRECB-1995-pt10-3-1`
- `GPO-CRECB-1995-pt10-3-2`
- `GPO-CRECB-1995-pt10-3-3`
- `GPO-CRECB-1995-pt10-4`
- `GPO-CRECB-1995-pt10-4-1`
- `GPO-CRECB-1995-pt10-4-2`
- `GPO-CRECB-1995-pt10-4-3`
- `GPO-CRECB-1995-pt10-5`
- `GPO-CRECB-1995-pt10-5-1`
- `GPO-CRECB-1995-pt10-5-2`
- `GPO-CRECB-1995-pt10-5-3`
- `GPO-CRECB-1995-pt10-6`
- `GPO-CRECB-1995-pt10-6-1`

## What this repository is not

The Record is a record of *proceedings*, not of outcomes. It reports what
was said and what was laid before each chamber; how each member voted is
not derivable from it, and the text of a measure is not here either.

Measures named in a document are cross-referenced by citation in that
document's front matter, as plain text rather than as links: the
sibling `us-congress-bills` shard for this Congress does not exist, and
a link to a repository nobody has created is a 404 repeated across
every document that carries it.
