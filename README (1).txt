RPDA8412 ICE Task 2 - analysis package v2.1 (15 October 2026)

v2.1 re-runs v2.0 on the corrected inputs:
  - interview dates and times added from the updated transcripts (P4 = 19 Oct 2026)
  - v2-only items no longer hold values for v1 respondents (integrity check passes)
  - scope expansion treated as a confirmed design decision (supervisor informed): survey and interviews are
    reported as ORIGINAL scope (illustrators, concept artists, animators) vs EXPANDED scope (design, social
    media and content, architecture and visualisation, platform work); interviews also have peripheral and
    stakeholder tiers
Results are otherwise identical to v2.0: 21 submissions, 14 eligible (6 original, 8 expanded); 11 interviews;
codebook v0.3 (29 codes); 7 candidate themes; multivariable modelling abandoned (ICE 1 contingency, n < 50).

RPDA8412_ICE2_analysis_v2.1.ipynb   executed notebook (outputs included)
data/                               DE-IDENTIFIED inputs only:
                                    survey_responses_v2_deid.xlsx (Q7.2 contact column removed)
                                    P1-P11_transcript_deid.txt (speaker-attributed, names/organisations redacted)
outputs/figures/                    the four figures
outputs/tables/                     all exported tables (*_v2.csv)

Colab: upload the notebook, put the 12 files from data/ anywhere in the Files panel (or in data/), then
Runtime > Run all. The setup cell finds the files and copies them into data/.

The original survey export still contains the Q7.2 contact column (names, emails, phone numbers). Keep it on
the institutional OneDrive only and never commit it, the recordings, the original transcripts or the
pseudonym key to Git.
