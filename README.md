# W3C DTD for XML Schema

This repository contains two versions of W3C's DTD for XML Schemas:
a version from 2000, and one from 2001.

Each version comprises two files: XMLSchema.dtd and datatypes.dtd.
XMLSchema.dtd is the main DTD, and it includes datatypes.dtd.

These were downloaded from the W3C website on February 4, 2016, from:

* 2000 version:
    * [http://www.w3.org/2000/10/XMLSchema.dtd](http://www.w3.org/2000/10/XMLSchema.dtd)
    * [http://www.w3.org/2000/10/datatypes.dtd](http://www.w3.org/2000/10/datatypes.dtd)
* 2001 version:
    * [http://www.w3.org/2001/XMLSchema.dtd](http://www.w3.org/2001/XMLSchema.dtd)
    * [http://www.w3.org/2001/datatypes.dtd](http://www.w3.org/2001/datatypes.dtd)

This package also includes OASIS catalog files that can be used to resolve these
DTDs from public identifiers, or from their canonical URIs (system identifiers)
without accessing the network.

Datatypes are described in the W3C recommendation [XML Schema Part 2: Datatypes Second
Edition](https://www.w3.org/TR/xmlschema-2/). Note that the latest version of that
document (from 28 October 2004 at the time of this writing) has a listing of the
[DTD for Datatype Definitions
(non-normative)](https://www.w3.org/TR/xmlschema-2/#dtd-for-datatypeDefs) in
Appendix B. That listing does not *exactly* match the version from 2001, but the
only differences are cosmetic: comments and whitespace.

