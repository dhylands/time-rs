# time-rs
Time formatting routines.

Implements time conversion using the posix epoch of Jan 1, 1970.

These routines support times prior to Jan 1, 1970 by using negative offsets.

Tm::format_iso_into formats into an already allocated buffer which allows for reduced
heap usage.

[![Build Status](https://travis-ci.org/dhylands/format-rs.svg?branch=master)](https://travis-ci.org/dhylands/format-rs)
