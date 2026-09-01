നവാംശം (Navamsha D9) & വർഗ്ഗോത്തമം (Vargottama): Play With It
================================================================================

.. raw:: html

   <style>
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
   </style>

Every rashi divides into 9 equal **നവാംശം** (Navamsha) segments of 3
degrees 20 minutes each -- the exact same span as a nakshatra pada on
the :doc:`rashi_nakshatra_interactive` page, just grouped by rashi (9
per sign) instead of by nakshatra (4 per nakshatra). This page is that
one extra layer of arithmetic: which sign a given Navamsha segment
lands in, and whether a planet's D1 and D9 signs coincide
(വർഗ്ഗോത്തമം, Vargottama).

Play With It
------------------

Drag the pointer around the wheel, or click anywhere on the ring, to
see any longitude's D1 രാശി and its computed D9 നവാംശം sign update
live, along with which of the 9 divisions it falls in and whether it's
വർഗ്ഗോത്തമം. The reference grid below shows the complete 12x9 = 108-cell
mapping -- drag around the wheel and watch the active row highlight
move through it.

.. raw:: html
   :file: _static/navamsa_widget.html

Why the Starting Sign Shifts by Modality
--------------------------------------------------------

The 9 divisions of a rashi don't always start counting from that
rashi itself. Which sign they start from depends on the rashi's
**modality** (Guna):

.. list-table::
   :class: longtable
   :header-rows: 1
   :widths: 25 35 40

   * - Modality
     - Rashis
     - Where the 9 divisions start
   * - ചരം (Movable / Chara)
     - Mesha, Karka, Tula, Makara
     - From the rashi itself
   * - സ്ഥിരം (Fixed / Sthira)
     - Vrishabha, Simha, Vrishchika, Kumbha
     - From the 9th sign counting from it
   * - ദ്വിസ്വഭാവം (Dual / Dwisvabhava)
     - Mithuna, Kanya, Dhanu, Meena
     - From the 5th sign counting from it

A structural fact worth noticing, and one the widget's wheel makes
visible directly: whichever of the 12 rashis you start from, the sign
those 9 divisions count from is **always itself movable** -- not a
coincidence, but a direct consequence of the three modalities being
spaced 3 rashis apart around a 12-rashi wheel where movable signs sit
at positions 0, 3, 6, 9.

വർഗ്ഗോത്തമം (Vargottama): When D1 and D9 Agree
--------------------------------------------------------

Out of a rashi's 9 divisions, **exactly one** always maps back to that
same rashi in D9 -- verified directly against the full 108-cell table,
not asserted on faith. A planet placed in that one division is
Vargottama: its D1 (Rashi) placement and D9 (Navamsha) placement
agree, which classical sources treat as a marker of unusual stability
across the chart. This page stops at *whether* Vargottama occurs --
what it's traditionally said to mean for a chart is interpretation,
not covered here.

Sources & Scope
--------------------

The Navamsha division rule (movable signs count from themselves,
fixed signs from the 9th sign from them, dual signs from the 5th) and
the resulting Vargottama definition follow the standard Parashari
framework used across essentially every Jyotisha school, including
Kerala. The rule was independently verified against a published
worked example (Aries 11 degrees 35 minutes falling in the 4th of 9
divisions, correctly mapping to Karka/Cancer) before publishing, and
the two structural invariants highlighted above (the starting sign is
always movable; exactly one Vargottama division per rashi) were
verified by direct computation across the full 108-cell table rather
than assumed. If a specific reference text -- especially anything
Kerala-school-specific -- describes a detail differently, that text
wins; flag it and this page gets corrected.
