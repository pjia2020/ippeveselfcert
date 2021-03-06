IPP Everywhere™ v1.1 Printer Self-Certification Tools
=====================================================

This directory contains the IPP Everywhere™ v1.1 Printer Self-Certification
tools.

In addition to the files in this directory, you must also download and
extract one or more PWG Raster Format file archives from
<https://ftp.pwg.org/pub/pwg/ipp/examples/>

These archives are used for the Document Data tests.

> Note: Tests are intended to be run on an isolated network, or at least when no
> other users are printing using the target printer.  Otherwise the test scripts
> will fail randomly.


Contents
--------

Scripts for running the self-certification tests:

- "dnssd-tests.bat": DNS-SD Tests for Windows
- "dnssd-tests.sh": DNS-SD Tests for Linux and macOS

- "ipp-tests.bat": IPP Tests for Windows
- "ipp-tests.sh": IPP Tests for Linux and macOS

- "document-tests.bat": Document Data Tests for Windows
- "document-tests.sh": Document Data Tests for Linux and macOS

Tools:

- "ippeveprinter": Sample IPP Everywhere printer, useful for testing
- "ippevesubmit": IPP Everywhere Printer Self-Certification submission tool
- "ippfind": Tool for finding printers with DNS-SD (Bonjour)
- "ipptool": IPP test tool

Documentation:

- "LICENSE" and "NOTICE": Software license
- "man-*.html": HTML documentation for the tools
- "README.md": This README file


Getting Support and Other Resources
-----------------------------------

The IPP Everywhere home page provides access to all information relevant to
IPP Eveywhere: <https://www.pwg.org/ipp/everywhere.html>

The "ippeveselfcert@pwg.org" mailing list is used to discuss IPP Everywhere
Printer Self-Certification.  You can subscribe from the following page:
<https://www.pwg.org/mailman/listinfo/ippeveselfcert>


Legal Stuff
-----------

Copyright © 2014-2020 by the IEEE-ISTO Printer Working Group.
Copyright © 2007-2019 by Apple Inc.
Copyright © 1997-2007 by Easy Software Products.

This software is provided under the terms of the Apache License, Version 2.0.
A copy of this license can be found in the file `LICENSE`.  Additional legal
information is provided in the file `NOTICE`.

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied.  See the License for the
specific language governing permissions and limitations under the License.
