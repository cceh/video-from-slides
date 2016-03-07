video-from-slides
=================

Merge a set of slides into one continuous video with a countdown timer.
Good for posterslams.

Just a quick shell script, nothing too fancy. But it gets the job done.


Usage
-----

1. Put all the slides, one slide per PDF, in the `slides/` directory;
2. adjust the parameters in `video.param`;
3. run `./video-from-slides VIDEO.MP4`.

The script will generate a video called `VIDEO.MP4` with all the slides
concatenated and a countdown displayed in the last seconds.


Requirements
------------

* `avconv` from `libav` (available in the `libav-tools` package).


Authors and licence
-------------------

This project has been developed at the Cologne Center for eHumanities
by the following people:

* Gioele Barabucci

This project has been released under the ISC licence. See the `LICENCE.ISC`
file or <http://opensource.org/licenses/ISC> for more details.
