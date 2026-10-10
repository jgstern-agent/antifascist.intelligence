# Blind trial: unblinding map

Judging folders sit outside the repository, under `/home/user/blindtrial/`. Each holds one `manuscript.md`, rendered with `finishing/tools/render_markdown.py` as of 2026-10-10, with the "Rendered … from <commit>" line removed. Folder names were drawn at random, and which folder got which version was decided by a random draw.

| Folder | Version | Commit | Date | Phase |
| --- | --- | --- | --- | --- |
| `r716fc2` | Earlier | `920e6b9` | 2026-10-02 01:21 | The LaTeX manuscript just after its prose was replaced with the condensed reworking; the condensed file's last edit was `9b34a59`, 00:33 the same night. Rendered from a separate worktree with the 2026-10-10 render script. |
| `r16e30c` | Later | `1a2b99d` (manuscript identical to `683c828`) | 2026-10-10 | After the consolidation passes D-690 to D-701 and the proofs of 2026-10-10. |

Word counts by the same rule (main text excluding footnote text; footnotes; appendices from "A." on):

| Folder | Main text | Footnotes | Appendices | Total |
| --- | --- | --- | --- | --- |
| `r716fc2` | 106,788 | 810 | 9,247 | 116,570 |
| `r16e30c` | 100,014 | 825 | 22,611 | 123,179 |

Run 1: one Haiku judge per folder, effort medium, identical instructions apart from the folder path.
