പഞ്ചാംഗം: തിഥി & യോഗം (Panchanga: Tithi & Yoga): Play With It
================================================================================

.. raw:: html

   <style>
     @import url('https://fonts.googleapis.com/css2?family=Manjari:wght@100;700&family=Noto+Sans+Malayalam:wght@500&display=swap');
     div.document {
       background: #eef1ee;
       color: #000000;
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
     div.document strong { color: #000000; font-weight: 700; }
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
   </style>

**പഞ്ചാംഗം** (Panchanga, "five limbs") is the traditional Hindu
almanac; this page covers two of its five limbs, **തിഥി** (Tithi)
and **യോഗം** (Yoga). Both are pure arithmetic on the same two
quantities -- the Sun's and Moon's real sidereal longitudes -- reusing
the exact Meeus Sun/Moon toolkit already verified for the
:doc:`vimshottari_dasha_interactive` and :doc:`gulika_interactive`
pages. Vara (weekday) and Nakshatra, the other two computable limbs,
already have their own coverage elsewhere on this site; Karana (a
half-tithi subdivision) is out of scope here.

Play With It
------------------

Enter a date, local time, and UTC offset. The widget computes the
Sun's and Moon's real sidereal longitudes for that instant and
derives both the current Tithi and the current Yoga live, along with
a side-by-side comparison of what each quantity would be if computed
tropically instead of sidereally.

.. raw:: html
   :file: _static/panchanga_widget.html

A Difference and a Sum, Not Two Unrelated Rules
--------------------------------------------------------

Tithi and Yoga are defined by the same two inputs combined two
different ways:

- **Tithi** = (Moon longitude − Sun longitude), divided into 30 steps
  of 12° each.
- **Yoga** = (Moon longitude + Sun longitude), divided into 27 steps
  of 13°20′ each.

That single difference in arithmetic (subtraction vs. addition) has
a real, verifiable consequence: **Tithi doesn't care whether the
longitudes are sidereal or tropical, and Yoga does.** Subtracting two
longitudes that were each shifted by the same ayanamsa cancels that
shift out entirely -- Tithi comes out identical either way, confirmed
by direct computation in this page's build notes. Summing them does
the opposite: the ayanamsa gets added in *twice*, so a tropical
calculation of Yoga is off by 2×ayanamsa from the correct sidereal
(nirayana) value -- currently around 48-50°, comfortably more than a
full 13°20′ Yoga span. The "Sidereal vs. tropical" panel on this page
makes that concrete: the Tithi column never changes between the two,
and the Yoga column very often lands on a genuinely different named
Yoga.

Each half-open 12° (or 13°20′) span belongs to the tithi (or yoga)
that *starts* at its lower boundary -- which is what makes Amavasya
and Purnima the closing tithi of their own paksha rather than a 31st
entry, and is verified in this page's build notes by checking every
exact multiple of the span boundary explicitly, not just spot-checked
values.

Sources & Scope
--------------------

Sun and Moon longitudes are Jean Meeus's own formulas (Ch.24
low-accuracy Sun, the same truncated ELP2000-82B lunar theory from
Ch.45/47) -- the identical code already verified against Meeus's own
worked examples for the Vimshottari Dasha and Gulika pages, not
re-derived or re-typed here. The 30 Tithi names and the 27 Yoga
names, and their formal 12°/13°20′ definitions, were checked against
Wikipedia's "Tithi" and "Nityayoga" articles and cross-checked against
several independent astrology-site listings, which all agree on both
the names and the definitions.

Two disclosed simplifications, carried over unchanged from the rest
of this site: longitudes are geocentric rather than topocentric, and
UT is treated as Terrestrial Time (ignores Delta-T, under a minute
of error for 20th/21st-century dates). If a specific reference text
describes a detail differently, that text wins; flag it and this
page gets corrected.
