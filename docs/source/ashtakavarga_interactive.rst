അഷ്ടകവർഗ്ഗ ശോധന (Ashtakavarga Shodhana) & കക്ഷ്യ (Kakshya): Play With It
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

**അഷ്ടകവർഗ്ഗം** (Ashtakavarga, "eight-source strength") scores each
sign 0-8 based on how many of the 7 planets plus the Ascendant
traditionally consider it favorable. This page doesn't build those
raw scores (a large, separately-verifiable lookup table on its own --
see Scope below); it covers the two **reduction algorithms** applied
afterward, and the **Kakshya** subdivision used for transit timing --
all pure, deterministic arithmetic on whatever raw scores you give it.

Play With It
------------------

Enter a planet's raw 12-sign bindu count and mark which signs
currently hold a planet, to see both reduction stages live. It
defaults to a real published example so you can see it work before
changing anything.

.. raw:: html
   :file: _static/ashtakavarga_widget.html

Two Reductions, In Order
--------------------------------

**Trikona Shodhana** groups the 12 signs into 4 triads by element
(fire: Mesha/Simha/Dhanu; earth: Vrishabha/Kanya/Makara; air:
Mithuna/Tula/Kumbha; water: Karka/Vrishchika/Meena) and subtracts each
triad's lowest bindu count from all three of its members -- so every
triad ends up with at least one sign at 0.

**Ekadhipatya Shodhana** then handles the 5 sign-pairs sharing one
lord (Mars: Mesha/Vrishchika; Venus: Vrishabha/Tula; Mercury:
Mithuna/Kanya; Jupiter: Dhanu/Meena; Saturn: Makara/Kumbha -- Sun and
Moon are excluded, since they rule only one sign each). Whether and
how a pair reduces depends on which of the two signs currently holds
a planet:

.. list-table::
   :class: longtable
   :header-rows: 1
   :widths: 30 70

   * - Situation
     - Result
   * - Both signs occupied
     - No reduction -- checked first, unconditionally
   * - Either sign already at 0
     - No reduction -- nothing left to reduce
   * - Neither occupied, equal bindus
     - Both to 0
   * - Neither occupied, unequal
     - Both drop to the smaller value
   * - One occupied (bigger value), one vacant
     - Vacant drops to 0; occupied unchanged
   * - One occupied (smaller value), one vacant
     - Vacant drops to *match* the occupied value; occupied unchanged

That "both occupied" case has to be checked **before** the tie case,
not after -- a both-occupied pair that happens to be tied must stay
untouched, and checking for ties first would wrongly zero it. This
exact ordering mistake showed up during development and was caught by
re-testing against the worked example below, not by reasoning about
the rule in the abstract.

Verified Against a Real Worked Example
--------------------------------------------------------

Both reductions above were checked against **Mahatma Gandhi's
horoscope**, published with full raw bindus and both reduction stages
worked out, in M.S. Mehta's *Ashtakvarga: Concept & Application*.
That single example happens to exercise both branches of the mixed
occupancy case: the Sun's Bhinna Ashtakavarga shows a bigger-value
sign staying put while its smaller-value pair-mate drops to zero, and
the Moon's shows the opposite -- a smaller-value occupied sign staying
put while its bigger pair-mate drops down to *match* it, not to zero.
Reproducing both outcomes from one general algorithm is a much
stronger check than confirming either one alone, and this widget
defaults to that exact Sun example so you can see it firsthand.

Kakshya: An 8-Fold Subdivision for Transit Timing
--------------------------------------------------------

Independent of the reductions above, every sign also divides into 8
equal **Kakshyas** of 3 degrees 45 minutes each (30 divided by 8),
ruled in a fixed order: ശനി (Saturn),
വ്യാഴം (Jupiter), ചൊവ്വ (Mars), സൂര്യൻ (Sun), ശുക്രൻ (Venus), ബുധൻ
(Mercury), ചന്ദ്രൻ (Moon), ലഗ്നം (Lagna). This sequence restarts
identically at the beginning of every sign -- it has nothing to do
with rashi boundaries, only with degree-within-sign.

Sources & Scope
--------------------

The Trikona Shodhana rule, the Ekadhipatya Shodhana rule (all six
occupancy cases above), the Rashi Gunakar table (used for the Rashi
Pinda figure shown), and the Kakshya order and span were all
cross-checked against M.S. Mehta's *Ashtakvarga: Concept &
Application*, using its worked Mahatma Gandhi example as a golden
test case wherever it applied. This page deliberately does **not**
build the raw Bhinna Ashtakavarga contribution tables themselves (the
"how many of 8 sources favor each sign" lookup that produces the raw
bindus in the first place) -- those are a large, separately verifiable
dataset (roughly 670 individual entries across all 7 planets) that
deserves its own dedicated verification pass rather than being rushed
alongside the reduction algorithms. Graha Pinda, the other half of
Shodhya Pinda, needs a full chart's worth of planetary positions
rather than one planet's own table, so it's described here but not
built as an interactive calculator. If a specific reference text
describes a detail differently, that text wins; flag it and this page
gets corrected.
