Dumped using JavaScript by https://github.com/Brian151 (aka 'ETXAlienRobot201' / 'ETX' on http://marsmissionwiki.wikifoundry.com)

The data in these files may not be 100% accurate. 
This is mainly due to discrepencies in the CAMM format and CAC's level data.

Astro Level 5 uses a main base whose type and team depends on the player's current team,
the dump does not reflect that.

The Santa bonus level uses teams set according to the current opponent.

The Alien special ops uses a randomizer to set the obj paramater of about five units,
I'm not sure why, but the export does not reflect this.

Astro Special Ops 3 uses a randomizer to choose the spawn positon of
the present with the alien commander. This is not reflected, a single path was chosen.

Some levels override the construction options, this is not reflected in these dumps, either.

Most levels clear some area of the 'shroud', CAC's fog of war, CAMM doesn't yet support this.
The dumps are also missing that.

Most levels also contain indicators and camera re-focus instructions.
This data is also not present.

There also were cases due to CAMM being otherwise unable to read the data that has resulted
in null having to be given a default value. That said, the AI target parameter of units
is to be assumed always wrong in these dumps.

The dumped levels which will be referred to as the "default maps" will likely be updated over
time to reflect added or changed features in CAMM, and to fix incorrect data in the files.
