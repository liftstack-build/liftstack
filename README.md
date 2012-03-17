Introduction

Work In Progress, not ready for public use yet.

Phase 1:  A simple script to download and setup sbt, sbt-extras, and lifty.

Phase 2:  Add ability to choose servlet container or network stack - jetty or netty

Phase 3:  [Maybe, not sure this makes sense] add ability to select db - postgres, mongo, redis


Setup

Run the following at the commandline:

bash < <(curl https://raw.github.com/lift-stack/lift-stack/master/setup.sh)

or 

wget https://raw.github.com/lift-stack/lift-stack/master/setup.sh -O- | sh

or if you want to inspect the code before running it:

wget https://raw.github.com/lift-stack/lift-stack/master/setup.sh

sh setup.sh
