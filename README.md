# cpan-cullers - who can free up the most space from CPAN?

This is a script which works out who can free up the most space from
CPAN by deleting old releases.

It does this by grabbing the ls-lR.gz file from CPAN and processing that.

To see the top 20 offenders, just run:

    cpan-cullers | head -20

Or to see how much space a particular author could free up, run:

    cpan-cullers | grep NEILB

It's a complete hack, but gives a pretty good estimate of how much space
each author is hogging.

Neil Bowers
2017
