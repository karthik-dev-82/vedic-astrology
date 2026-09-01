താരാബലം (Tara Bala): Play With It
================================================================================

.. raw:: html

   <style>
     @import url('https://fonts.googleapis.com/css2?family=Manjari:wght@100;700&family=Noto+Sans+Malayalam:wght@500&display=swap');
     div.document {
       background: #eef1ee;
       color: #1c231d;
       font-family: Georgia, "Iowan Old Style", "Times New Roman", serif;
       line-height: 1.68;
       font-size: 17px;
       border: 1px solid #cdd6cc;
       border-radius: 4px;
       padding: 40px 48px 48px;
       margin: 12px 0 24px;
     }
     div.document h1 {
       font-family: inherit;
       font-weight: 400;
       font-size: 2.4rem;
       line-height: 1.12;
       color: #1c231d;
       border-bottom: 1px solid #cdd6cc;
       padding-bottom: 18px;
       margin: 0 0 30px;
     }
     div.document h2 {
       font-family: inherit;
       font-weight: 400;
       font-style: italic;
       font-size: 1.5rem;
       color: #1c231d;
       margin: 44px 0 10px;
       padding-top: 26px;
       border-top: 1px solid #cdd6cc;
     }
     div.document h2:first-of-type { border-top: none; padding-top: 0; margin-top: 30px; }
     div.document h3 {
       font-family: inherit;
       font-weight: 700;
       font-style: normal;
       font-size: 1.14rem;
       color: #7a2f3d;
       margin: 26px 0 8px;
     }
     div.document .headerlink {
       color: #5c675d;
       opacity: 0.5;
       text-decoration: none;
       font-size: 0.7em;
       margin-left: 8px;
     }
     div.document .headerlink:hover { opacity: 1; }
     div.document p { margin: 0 0 17px; }
     div.document strong { color: #1c231d; font-weight: 700; }
     div.document a { color: #7a2f3d; text-decoration: underline; text-decoration-color: #7a2f3d55; text-underline-offset: 2px; }
     div.document a:hover { text-decoration-color: #7a2f3d; }
     div.document ul, div.document ol { margin: 0 0 17px; padding-left: 26px; }
     div.document li { margin-bottom: 7px; }
     div.document hr { border: none; border-top: 1px solid #cdd6cc; margin: 40px 0; }

     div.document code.docutils.literal {
       font-family: ui-monospace, "SF Mono", Menlo, monospace;
       font-size: 0.86em;
       background: #f2f0ea;
       border: 1px solid #d8d4c8;
       color: #4a2f14;
       padding: 1px 5px;
       border-radius: 2px;
     }

     div.document div.highlight {
       background: #f2f0ea;
       border: 1px solid #d8d4c8;
       border-left: 3px solid #7a2f3d;
       border-radius: 0;
       padding: 14px 18px;
       margin: 4px 0 22px;
       overflow-x: auto;
     }
     div.document div.highlight pre {
       background: transparent;
       color: #2a2a24;
       font-family: ui-monospace, "SF Mono", Menlo, monospace;
       font-size: 0.86rem;
       line-height: 1.6;
       margin: 0;
     }
     div.document .highlight .c1 { color: #7a7266; font-style: italic; }
     div.document .highlight .k, div.document .highlight .kn, div.document .highlight .nb { color: #3d5c3d; font-weight: 600; }
     div.document .highlight .s1, div.document .highlight .s2 { color: #7a2f3d; }
     div.document .highlight .gp, div.document .highlight .gh { color: #7a2f3d; font-weight: 700; }
     div.document .highlight .nv, div.document .highlight .ss,
     div.document .highlight .vc, div.document .highlight .vg,
     div.document .highlight .vi, div.document .highlight .vm { color: #4a4470; }
     div.document .highlight .o, div.document .highlight .go { color: #6a6a5e; }

     div.document table.docutils {
       width: 100%;
       border-collapse: collapse;
       background: #ffffff;
       border: 1px solid #cdd6cc;
       margin: 6px 0 24px;
       font-size: 0.92rem;
       font-family: -apple-system, "Segoe UI", sans-serif;
     }
     div.document table.docutils th.head {
       text-align: left;
       padding: 9px 14px;
       font-size: 0.72rem;
       letter-spacing: 0.06em;
       text-transform: uppercase;
       color: #7a2f3d;
       border-bottom: 2px solid #7a2f3d;
       font-weight: 700;
     }
     div.document table.docutils td {
       padding: 9px 14px;
       border-bottom: 1px solid #cdd6cc;
       vertical-align: top;
     }
     div.document table.docutils tr.row-even { background: #f7f6f2; }
     div.document table.docutils tr.row-odd { background: transparent; }
     div.document table.docutils tr:last-child td { border-bottom: none; }
     div.document h1,
     div.document h2,
     div.document p {
       font-family: 'Manjari', sans-serif;
       font-weight: 100;
     }
     div.document strong {
       font-family: 'Manjari', sans-serif;
       font-weight: 700;
     }
     div.document table.docutils {
       font-family: 'Noto Sans Malayalam', sans-serif;
       font-weight: 500;
     }
   </style>

**താരാബലം** (Tara Bala, "star strength") groups all 27 nakshatras
into 9 named categories -- not by their fixed position in the zodiac,
like the :doc:`rashi_nakshatra_interactive` page's Atta and Gandantham
patterns, but **relative to a chosen reference point**: usually
someone's ജന്മനക്ഷത്രം (Janma Nakshatra, birth star). Which category a
given nakshatra falls into is pure counting -- the same `mod 9`
structure already used elsewhere on this site, just applied to a
distance instead of an absolute index.

Play With It
------------------

Drag the pointer to set the Janma Nakshatra. Every other nakshatra's
distance, Tara group, and traditional auspicious/inauspicious reading
recompute live in the table below -- drag the wheel around and watch
the whole table's classification rotate with it.

.. raw:: html
   :file: _static/tarabala_widget.html

The Counting Rule
--------------------

Counting is 1-based and inclusive: the reference nakshatra itself is
distance 1 (Janma Tara). From there, the 9 groups repeat three times
across the 27 nakshatras:

.. list-table::
   :class: longtable
   :header-rows: 1
   :widths: 15 20 20 45

   * - #
     - Group
     - Distance from Janma
     - Traditional reading
   * - 1
     - ജന്മ (Janma)
     - 1, 10, 19
     - Neutral -- the reference point itself
   * - 2
     - സമ്പത്ത് (Sampat)
     - 2, 11, 20
     - Auspicious
   * - 3
     - വിപത്ത് (Vipat)
     - 3, 12, 21
     - Inauspicious
   * - 4
     - ക്ഷേമ (Kshema)
     - 4, 13, 22
     - Auspicious
   * - 5
     - പ്രത്യക് (Pratyak)
     - 5, 14, 23
     - Inauspicious
   * - 6
     - സാധന (Sadhana)
     - 6, 15, 24
     - Auspicious
   * - 7
     - നൈധന (Naidhana)
     - 7, 16, 25
     - Inauspicious
   * - 8
     - മിത്ര (Mitra)
     - 8, 17, 26
     - Auspicious
   * - 9
     - പരമ മിത്ര (Parama Mitra)
     - 9, 18, 27
     - Auspicious

Because the pattern repeats every 9 nakshatras and 27 divides evenly
by 9, every one of the 9 groups always contains **exactly 3** of the
27 nakshatras, for any reference point at all -- verified directly by
computing the full 27x27 table of every possible (reference, target)
pair, not assumed from the rule alone.

Sources & Scope
--------------------

The 9-group counting rule and the auspicious/inauspicious pattern
follow the standard Navatara framework used across essentially every
Jyotisha school, including Kerala, and were independently verified
against multiple outside sources before publishing. The
auspicious/inauspicious labels are the traditional classification this
system is defined by, not a claim this page asserts as objective fact
-- what a given Tara group is said to bring is interpretation; the
counting mechanics that assign a nakshatra to a group are what's
verified here. If a specific reference text describes a detail
differently, that text wins; flag it and this page gets corrected.
