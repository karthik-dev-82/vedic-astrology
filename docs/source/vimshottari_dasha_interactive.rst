വിംശോത്തരി ദശ (Vimshottari Dasha): Play With It
================================================================================

**ദശ** (dasha) periods assign each planet a stretch of a person's
life during which it is the ruling "time-lord." Which planet rules
when is not interpretation -- it is arithmetic, driven entirely by
where the Moon sat, at birth, inside the 27-nakshatra cycle from the
:doc:`rashi_nakshatra_interactive` page. This page is that arithmetic
layer only: real dates computed from two inputs, not what any period
*means*.

Play With It
------------------

Set a birth date and drag the Moon to any നക്ഷത്രം position. The
120-year മഹാദശ (Mahadasha) timeline rebuilds live from just those two
inputs -- click any period to expand its അന്തർദശ (Antardasha) and
പ്രത്യന്തർദശ (Pratyantardasha) sub-periods. Whichever period contains
today's date is marked and auto-expanded.

.. raw:: html
   :file: _static/vimshottari_dasha_widget.html

The Fixed 120-Year Cycle
--------------------------------

Vimshottari means "of 120" -- the 9 classical grahas each get a fixed,
unequal share of a 120-year cycle, always in the same order:
കെതു (Ketu) 7, ശുക്രൻ (Venus) 20, സൂര്യൻ (Sun) 6, ചന്ദ്രൻ (Moon) 10,
ചൊവ്വ (Mars) 7, രാഹു (Rahu) 18, വ്യാഴം (Jupiter) 16, ശനി (Saturn) 19,
ബുധൻ (Mercury) 17. These 9 numbers are not adjustable or derived --
they are the fixed input the entire system is built from, and they
are exactly the same 9-lord order the rashi/nakshatra page's Atta and
Gandantham patterns are keyed to (nakshatra index mod 9). Venus,
the longest, gets a sixth of the whole cycle; the Sun, the shortest,
gets one twentieth.

Balance of Dasha at Birth: Why the First Period Is Never Full
--------------------------------------------------------------------

A person is essentially never born at the exact instant a nakshatra
begins. The Moon's position, at birth, is some fraction of the way
through its nakshatra -- and that elapsed fraction is what the whole
timeline is anchored to:

- **Starting lord**: whichever of the 9 grahas rules the Moon's birth
  nakshatra (nakshatra index mod 9 -- the same rule the earlier page
  uses for nakshatra lords).
- **Balance remaining**: ``(1 - elapsed fraction through that
  nakshatra) x that lord's full years``. Someone born 12.5% into a
  nakshatra ruled by Venus (20 years) starts life with 87.5% of a
  Venus Mahadasha left -- 17.5 years -- not the full 20.
- Every Mahadasha *after* that first one runs its full, un-shortened
  length, cycling through the remaining 8 lords in the fixed order
  and wrapping back to the start once all 9 have run.

This is also why a person's full dasha timeline from birth almost
never sums to a clean 120 years: the first period is a fragment, so a
complete lap through all 9 lords totals ``120 - elapsed portion
already spent before birth``.

Self-First Nesting: Antardasha and Pratyantardasha
--------------------------------------------------------

Each Mahadasha is itself divided into 9 അന്തർദശ (Antardasha)
sub-periods -- and each Antardasha divides again into 9 പ്രത്യന്തർദശ
(Pratyantardasha) sub-sub-periods. Both levels follow one identical
rule, applied recursively:

1. The 9 sub-periods are sized proportionally to the same fixed
   120-year shares (a sub-period's length = parent period's length
   x its own lord's years / 120).
2. The sub-period sequence always **starts with the parent period's
   own lord** -- a Venus Mahadasha's first Antardasha is Venus-Venus,
   before cycling Sun, Moon, Mars, Rahu, Jupiter, Saturn, Mercury,
   Ketu.

Because someone is also never born at the exact start of a Mahadasha,
the same balance logic cascades downward: the widget computes each
period's sub-periods against its *full* conceptual span (including
the portion before birth), then only displays the part landing on or
after birth -- which is why the very first Antardasha and
Pratyantardasha shown are usually shorter than a full 1/120th share,
while every later one at the same level is exact.

Sources & Scope
--------------------

The 9-lord order, the fixed 120-year allocation, the balance-of-dasha
rule keyed to the Moon's elapsed nakshatra fraction, and the
self-first proportional nesting rule for Antardasha and
Pratyantardasha here follow the standard Vimshottari system used
across essentially every Jyotisha school, including Kerala. Dates are
computed using a 365.25-day mean year, the convention most Vimshottari
calculators use. This page stops at Pratyantardasha; deeper levels
(Sookshma, Prana) follow the identical self-first proportional rule
recursively and are a natural future extension, not covered here.
If a specific reference text -- especially anything Kerala-school-
specific -- describes a detail differently, that text wins; flag it
and this page gets corrected.
