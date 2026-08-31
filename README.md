# voter-feed

A live wire on elections worldwide: who paid for them, who was kept from
voting, who counted the ballots, and whether the result was real.

Built after the Voter Suppression section on Welcome to Your Galaxy and its
four numbered pillars.

## The nineteen subjects

**The open-wallet count** — campaign finance, outside spending and Super PACs,
dark money and undisclosed donors, foreign money and its routes.

**Foreign infiltration** — covert influence, hack-and-leak, interference through
local proxies; and the propaganda and disinformation it pays for.

**Voter suppression** — identification rules, polling closures, mail and early
voting restrictions, registers and purges, and who is eligible at all.

**Electoral corruption** — vote buying and clientelism, ballot stuffing and
rigged counts, electoral violence, removing the opposition, control of the
airwaves, and who runs and adjudicates the vote.

Three more the section implies rather than lists, because its argument does not
hold without them: drawing the districts, the advantage of already being in
(where its 85 per cent and 90 per cent figures land), and measuring whether it
was real. Plus what is set against all of it.

## The gate

The horse race is refused, and it is most election coverage: poll leads,
prediction markets, seat projections, rallies, stump speeches, debate nights,
gaffes, endorsements, concession and victory speeches, approval ratings. So is
the word in its other senses — election to a board, a hall-of-fame vote,
natural selection.

A story no subject will claim is refused and counted as refused, rather than
filed under a fallback subject it did not earn.

## Weight

A decision (2), institutional material (2), a measured figure (1), a pending
decision with a date (1), a named jurisdiction (1), a primary source (1). At
three or more it is marked consequential.

## Sources

183 wires. 29 direct feeds carried over from the sibling repos where they are
already proven, plus 138 Google News locale searches across 26 languages with
24 rotating queries, and 16 subject searches.

Worth adding, with URLs you have opened: International IDEA, the Electoral
Integrity Project, OSCE/ODIHR, the Carter Center, NDI, IFES, the ACE Project,
OpenSecrets, ACLED and the Brennan Center. Those are the specialist bodies for
this subject and would strengthen the direct list considerably.

## Running it

    python3 harvest_voter.py
    python3 harvest_voter.py --dry-run
    python3 verify_sources.py
