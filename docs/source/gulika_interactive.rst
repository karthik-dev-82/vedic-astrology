ഗുളിക/മാണ്ഡി (Gulika / Mandi): Play With It
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
   </style>

**ഗുളിക** (Gulika, also called Mandi -- "son of Saturn") is a
mathematical point, not a planet: a longitude the Kerala tradition
treats as carrying Saturn's influence, derived entirely from birth
weekday, sunrise, and sunset. This page is the biggest astronomical
build on this site so far -- it computes a real Ascendant from real
sunrise/sunset times, not from manually-entered longitudes like the
:doc:`sphuta_interactive` page.

Play With It
------------------

Enter a birth date, local time, timezone, latitude, and longitude.
The widget finds real sunrise and sunset for that date and place,
divides the day (or night) into 8 equal parts by weekday, identifies
which part is Saturn's, and computes the actual Ascendant at the
exact clock moment that part begins.

.. raw:: html
   :file: _static/gulika_widget.html

The Weekday Rule, Derived Rather Than Memorized
--------------------------------------------------------

Both day and night divide into 8 equal segments, 7 ruled by the
classical planets and the 8th left to Rahu. Rather than two separate
lookup tables (one for day births, one for night), both reduce to
**one fixed 7-planet cycle** (Sun, Moon, Mars, Mercury, Jupiter,
Venus, Saturn) and a starting point:

- **Day births** start the cycle at that weekday's own ruling planet.
- **Night births** start 5 planets further along the same cycle (a
  half-rotation of the 8-slot day/night structure) -- which happens
  to always land you on the ruler 4 positions past the weekday lord,
  once Rahu's fixed 8th-place is accounted for.

This single rule reproduces all 14 published values (which segment
Saturn falls in, for each of 7 weekdays, for both day and night)
exactly -- verified by computation, the same way this site derives
Atta/Gandantham and Tara Bala from their own underlying cycles rather
than hardcoding lookup tables.

Verified by What Should Be True, Not Just What's Published
--------------------------------------------------------------------------

Sun position and sidereal time here are checked against Jean Meeus's
own worked examples, the same discipline used on the
:doc:`vimshottari_dasha_interactive` page. But the Ascendant formula
itself doesn't appear in that edition of Meeus's book, so it was
independently re-derived from 3D vector geometry (the ecliptic
circle's intersection with the horizon plane) rather than taken on
faith from a web source -- and then verified by checking the property
that actually *defines* an Ascendant: at the computed longitude, the
Sun's geometry places it exactly on the horizon, and rising (not
setting -- the Descendant satisfies the same equation, so this second
check matters). Sunrise and sunset were verified the same way: at the
computed times, the Sun's altitude comes out to exactly the standard
-0.8333 degrees used to define "rise" and "set," across hundreds of
random dates and locations.

That verification process caught two real bugs before they shipped.
Converting an hour-angle offset into elapsed clock time needs the
Sun's own rate of apparent motion (about 360 degrees per day) --
not the sidereal rate (about 360.986 degrees per day) that governs
fixed stars, which is what an earlier draft used everywhere,
producing rise/set times measurably wrong at higher latitudes.
Separately, the widget's visual timeline for which planet rules each
of the 8 segments used the literal typed calendar date's weekday
even for a pre-dawn birth, whose weekday should shift to the
*previous* day under the sunrise-to-sunrise convention Vedic timekeeping
uses -- the Saturn highlighting itself was already correct, but every
other segment's label was not.

Sources & Scope
--------------------

The Sun position formula (Meeus's own "low accuracy," 0.01-degree
method) and sidereal time formula are Jean Meeus's, verified against
his own published worked examples. The Ascendant formula was
independently derived and verified by the on-horizon-and-rising
property described above, not copied from an unverified source. The
weekday day/night segment rule was derived from a single 7-planet
cycle and matches all 14 published values. Two disclosed
simplifications: this uses a simplified geometric sunrise/sunset
model (not valid inside the polar circles, and not corrected for
atmospheric refraction beyond the standard -0.8333 degree constant),
and the geocentric (not topocentric) Sun position already used
elsewhere on this site. If a specific reference text describes a
detail differently, that text wins; flag it and this page gets
corrected.
