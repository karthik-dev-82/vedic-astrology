Vedic Astrology
===================

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

Personal study notes on Jyotisha (Vedic astrology), with a lean
toward the Kerala school where source material allows it. Built the
same way as the reference material this grew out of: real, checkable
mechanics first, wrapped in a small interactive widget wherever a
static explanation would leave the actual structure invisible.

.. toctree::
   :hidden:
   :maxdepth: 2
   :caption: Foundations

   rashi_nakshatra_interactive
   vimshottari_dasha_interactive
   navamsa_interactive
   tarabala_interactive
   dignity_interactive
   jaimini_interactive
   sphuta_interactive
   ashtakavarga_interactive
   gulika_interactive
   panchanga_interactive

Foundations
-----------------

.. list-table::
   :class: longtable
   :header-rows: 1
   :widths: 25 35 40

   * - Page
     - What it covers
     - Key terms
   * - :doc:`rashi_nakshatra_interactive`
     - Interactive rashi/nakshatra/pada wheel (Malayalam-first) -- drag to any longitude and see its rashi, nakshatra, pada, both lords, and its Atta split or Gandantham junction live
     - rashi, nakshatra, pada, rashi lord, nakshatra lord, Atta, Gandantham
   * - :doc:`vimshottari_dasha_interactive`
     - Interactive 120-year Vimshottari Dasha timeline -- enter a birth date/time/timezone, get the Moon's real computed sidereal position and a live Mahadasha/Antardasha/Pratyantardasha timeline
     - Vimshottari, Mahadasha, Antardasha, Pratyantardasha, balance of dasha, ayanamsa
   * - :doc:`navamsa_interactive`
     - Interactive Navamsha (D9) wheel -- drag to any longitude and see its D1 rashi and computed D9 sign live, whether it's Vargottama, and the full 12x9 mapping grid
     - Navamsha, D9, Vargottama, modality, movable, fixed, dual
   * - :doc:`tarabala_interactive`
     - Interactive Tara Bala wheel -- drag to set the Janma Nakshatra and see all 27 nakshatras' relative Tara group and traditional auspicious/inauspicious reading update live
     - Tara Bala, Janma Nakshatra, Navatara, Sampat, Vipat, Kshema
   * - :doc:`dignity_interactive`
     - Interactive planetary dignity & aspects wheel -- pick a graha, drag it anywhere in the zodiac, see its exaltation/own-sign/debilitation status and aspected signs live
     - dignity, exaltation, debilitation, Moolatrikona, own sign, drishti, aspects
   * - :doc:`jaimini_interactive`
     - Interactive Chara Karaka ranking and generic Arudha Pada calculator -- covers Arudha Lagna and Upapada Lagna as the same mechanism applied to house 1 and house 12
     - Chara Karaka, Atmakaraka, Darakaraka, Arudha Lagna, Upapada Lagna, Jaimini
   * - :doc:`sphuta_interactive`
     - Interactive Kerala Sphuta calculator -- set Lagna/Moon/Mandi and see all 5 Sphuta points and their built-in consistency check update live
     - Sphuta, Trisphuta, Prana Sphuta, Deha Sphuta, Mrityu Sphuta, Mandi, Prashna Marga
   * - :doc:`ashtakavarga_interactive`
     - Interactive Ashtakavarga Shodhana & Kakshya calculator -- enter raw bindus and occupancy to see Trikona and Ekadhipatya Shodhana live, verified against a real published worked example
     - Ashtakavarga, Trikona Shodhana, Ekadhipatya Shodhana, Rashi Pinda, Kakshya
   * - :doc:`gulika_interactive`
     - Interactive Gulika/Mandi calculator -- enter a real birth date/time/place, get real sunrise/sunset and a computed Ascendant at Saturn's weekday segment, verified by independent astronomical derivation
     - Gulika, Mandi, Upagraha, Ascendant, sunrise, sunset, weekday lord
   * - :doc:`panchanga_interactive`
     - Interactive Panchanga Tithi & Yoga calculator -- enter a date/time/timezone, get real sidereal Sun/Moon longitudes and the current Tithi and Yoga live, plus a sidereal-vs-tropical comparison showing why Yoga needs the ayanamsa and Tithi doesn't
     - Panchanga, Tithi, Yoga, Paksha, ayanamsa, nirayana
