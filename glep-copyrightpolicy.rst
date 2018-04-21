---
GLEP: 76
Title: Copyright Policy
Author: Richard Freeman <rich0@gentoo.org>,
        Alice Ferrazzi <alicef@gentoo.org>,
        Ulrich Müller <ulm@gentoo.org>,
        Robin H. Johnson <robbat2@gentoo.org>
Type: Informational
Status: Draft
Version: 1
Created: 2013-04-23
Last-Modified: 2018-04-20
Post-History: 
Content-Type: text/x-rst
---


Status
======

The policies on this page have no effect!  These are draft policies up
for discussion, not final versions.


Abstract
========


Motivation
==========

The copyright ownership of Gentoo materials is ambigious due to
historical factors, and this GLEP attempts to improve the process
going forward.

In the beginning (2000 or earlier), the copyright header stated that
*Gentoo Technologies, Inc.* was the copyright holder, without any
formal paperwork.  The formal assignment document was however only
introduced in early 2004.  The assignment had many objectors (mostly
on the ``gentoo-core`` mailing list).  The developer recruiting
procedures attempted to require signing of the document as a condition
for becoming a developer, but it was not applied to pre-existing
developers, or those that objected.

Later, the *Gentoo Foundation* was established, and copyrights were
formally transfered (including nullifying original developer
assignments to *Gentoo Technologies, Inc.*), and the copyright header
was updated.  The formal assignment document text was updated in 2006,
but the formal assignment process had already been abandoned in
mid-2004.

Throughout this, the presence of copyright headers existed as a
policy, and continues to exist to this day.  Some files also still
contain or have in the past contained additional copyright headers,
attributing ownership to other parties.

A detailed historical timeline is provided below [TODO: link]

The policy to have copyright notices ascribing copyright ownership to the
Gentoo Foundation caused an issue when Gentoo developers forked another project
and hosted the fork on Gentoo infrastructure.  To comply with the previous
policy the copyright notices were modified, which caused concerns with the
project the files were forked from.  Our previous policy completely neglected
the possibility that Gentoo might want to host files that were not created
internally.

Finally, since the early days of Gentoo new ideas around copyright
licensing have become more popular, such as the FSFe's Fiduciary
License Agreement [#FLA]_, which takes a copyleft approach to copyright licensing,
while also better complying with copyright laws in nations that have
author's rights.

The goal here was to create a policy that was both flexible enough to cover
forks and situations where Gentoo would not own the majority of the
copyright in a file, while also preserving our ability to formally
own copyrights on as much of our works as possible.



Specification
=============

Purpose / Scope
---------------

This policy documents how Gentoo contributors comply and document
copyright for any contributions made to Gentoo.  Anyone committing
documentation or sources to any repository hosted on Gentoo
infrastructure must comply with this policy.

Questions regarding this policy should be directed to the trustees or
the -project list.  Any concerns over possible copyright violations
should be directed to the Trustees if they cannot be worked out to
anyone's satisfaction with the appropriate maintainer.


Licensing of Gentoo Projects
----------------------------

Every Gentoo project must abide by the Gentoo Social Contract
[#SOCIAL-CONTRACT]_ and release its work under one or more of the
following:

a) The GNU General Public License, version 2 or later (GPL-2+)
   [#GPL-2]_.

b) The Creative Commons Attribution-ShareAlike 3.0 License
   (CC-BY-SA-3.0, only for documentation) [#CC-BY-SA-3.0]_.
   *[Note: or version 4.0, to be decided]*

c) A license approved as GPL compatible by the Free Software
   Foundation [#GPL-COMPAT]_.

Exceptions for other free software licenses will be granted by the
Gentoo Foundation on a case by case basis.

For easy reference, the license for each project should be documented
on the wiki page at [#PROJECTS]_.


Certificate of Origin
---------------------

All commits to Gentoo-hosted repositories shall be accompanied by a
certificate of origin.  The purpose of the certificate is to declare
that the contribution can be modified and redistributed in accordance
with the project's license.

For commits made using a VCS, the committer shall certify agreement
to the Gentoo DCO by adding ``Signed-off-by: Name <e-mail>`` to the
commit message as a separate line.

The following is the current Gentoo DCO 1.0::

    Gentoo Developer's Certificate of Origin 1.0

    By making a contribution to this project, I certify that:

    (a) The contribution was created in whole or in part by me, and I have
        the right to submit it under the free software license indicated
        in the file; or

    (b) The contribution is based upon previous work that, to the best
        of my knowledge, is covered under an appropriate free software
        license, and I have the right under that license to submit that
        work with modifications, whether created in whole or in part by
        me, under the same free software license (unless I am permitted
        to submit under a different license), as indicated in the file; or

    (c) The contribution is a license text (or a file of similar nature),
        and verbatim distribution is allowed; or

    (d) The contribution was provided directly to me by some other person
        who certified (a), (b), (c), or (d), and I have not modified it.

    I understand and agree that this project and the contribution are
    public and that a record of the contribution (including all personal
    information I submit with it, including my sign-off) is maintained
    indefinitely and may be redistributed consistent with this project or
    the free software license(s) involved.

The Gentoo DCO is licensed under a Creative Commons
Attribution-ShareAlike 3.0 Unported License [#CC-BY-SA-3.0]_.
It is based on the Linux Kernel DCO [#OSDL-DCO]_, released by Open
Source Development Labs, Inc. in 2005 under a CC-BY-SA-2.5 License.


Copyright Attribution
---------------------

All files hosted by Gentoo must contain an appropriate copyright
notice, as defined by this policy.

A proper copyright notice appears near the top of the file, and reads::

    Copyright YEARS LARGEST-CONTRIBUTOR [OTHER-CONTRIBUTORS] and others

The largest contributor is whatever entity owns copyright to some
portion of the largest number of lines in the file.  Additional
contributors can be listed, but this is neither required nor
recommended.  The “and others” text may be omitted if the explicitly
listed contributors hold copyright to the entire file.

Anyone finding a file out of compliance should log a bug against the
associated project/package providing as much information as possible.
Files that are not brought into compliance within 60 days or upon a
request for removal by a aggrieved copyright holder will be removed.
Any concerns not addressed by a maintainer can be appealed to the
Trustees.


Licensing to the Gentoo Foundation
----------------------------------

All are welcome and encouraged (but NOT required) to assign copyright
for their contributions to the Gentoo Foundation.  Doing so makes
compliance with this policy easier (fewer copyright holders to list),
and allows the Foundation to enforce copyrights and re-license content
if appropriate (this will only be done in accordance with the social
contract and the Gentoo FLA).

Copyright is assigned to the Foundation by electronically signing the
Gentoo Fiduciary License Agreement (FLA) [#GFLA]_.

The agreement may be signed BY **TODO...**  If the scope of the signed
agreement included future contributions, the contributor may document
their wish to stop assigning copyright by **TODO...**

A list of those who have signed this agreement and the scope of their
assignments may be found at **LINK**.  This list may be useful when
attributing copyright.


Rationale
=========

Key dates in Gentoo copyright history
=====================================

* 2000-01-03: *Gentoo Technologies, Inc.* established in New Mexico.

* 2000-07-28: `Earliest known CVS commit
  <https://sources.gentoo.org/cgi-bin/viewvc.cgi/gentoo-x86/header.txt?revision=1.1&view=markup>`_
  in the Gentoo CVS repositories.  Made by Daniel Robbins to
  ``gentoo-x86/header.txt``
  ::

    # Copyright 1999-2000 Gentoo Technologies, Inc.
    # Distributed under the terms of the GNU General Public License, v2 or later
    # $header$


* 2000-10-09: `Earliest known version of the ebuild skeleton
  <https://sources.gentoo.org/cgi-bin/viewvc.cgi/gentoo-x86/skel.ebuild?revision=1.1&view=markup>`_.
  (``skel.ebuild``) in CVS

* 2004-01-20: Copyright assignment document added to CVS, with an
  assignee of *Gentoo Technologies, Inc.*, in both `text
  <https://sources.gentoo.org/cgi-bin/viewvc.cgi/gentoo/xml/htdocs/proj/en/devrel/copyright/assignment.txt?hideattic=0&view=log>`_
  and `PDF
  <https://sources.gentoo.org/cgi-bin/viewvc.cgi/gentoo/xml/htdocs/proj/en/devrel/copyright/assignment.pdf?hideattic=0&view=log>`_
  formats.  A related GuideXML page is `included
  <https://sources.gentoo.org/cgi-bin/viewvc.cgi/gentoo/xml/htdocs/proj/en/devrel/copyright-assignment/index.xml?hideattic=0&view=log>`_.

* 2004-05-28: *Gentoo Foundation, Inc.* established in New Mexico.

* 2004-07-12 or earlier: The recruiters stopped requiring the
  assignment document.  **TODO: document when/who/where recruiters were
  told to stop using the document.**

* 2005-05-19: Gentoo Technologies, Inc. files an **Assignment of
  Copyright** document, signed by Daniel Robbins, which transfers any
  copyrights held by *Gentoo Technologies, Inc.* over `All files to
  which Gentoo Technologies, Inc. may hold the copyright that existed
  in the Gentoo Concurrent Versions System (CVS) Repositories as of 25
  June 2004`.

* 2005-06-13: *Gentoo Technologies, Inc.* files a **recordation of
  copyright** with the United States Copyright Office, signed by
  Daniel Robbins, President.  The copyright is asserted over `Gentoo
  Concurrent Versions System (CVS) Repositories as of 25 June 2004`.

* 2005-06-13: *Gentoo Technologies, Inc.* provides a **Release from
  Contract Requirements** document, signed by Daniel Robbins.  The
  complete body of the document is as follows:
  ::
    Gentoo Technologies, Inc. does hereby release all individuals who
    have signed the contract known as the "Gentoo Technologies, Inc.
    Copyright Assignment Form" from future duties and obligations
    these individuals associated with that contract.  As of this date
    any provision of that contract requiring any future duties is
    hereby nullified.

* 2005-06-25: First CVS commit `changing
  <https://sources.gentoo.org/cgi-bin/viewvc.cgi/gentoo-x86/header.txt?revision=1.10&view=markup>`_
  copyright header to *Gentoo Foundation*.

* 2006-08-23: Copyright assignment document assignee `updated
  <https://sources.gentoo.org/cgi-bin/viewvc.cgi/gentoo/xml/htdocs/proj/en/devrel/copyright/assignment.txt?hideattic=0&r1=1.1&r2=1.2>`_
  to *Gentoo Foundation, Inc.*

* 2007-01-27: Copyright assignment document `removed
  <https://sources.gentoo.org/cgi-bin/viewvc.cgi/gentoo/xml/htdocs/proj/en/devrel/copyright/assignment.txt?view=log&hideattic=0>`_.


References
==========

.. [#SOCIAL-CONTRACT] Gentoo Social Contract,
   https://www.gentoo.org/get-started/philosophy/social-contract.html

.. [#GPL-2] GNU General Public License, version 2 or later,
   http://www.gnu.org/licenses/gpl-2.0.html

.. [#CC-BY-SA-3.0] Creative Commons Attribution-ShareAlike 3.0
   Unported License, http://creativecommons.org/licenses/by-sa/3.0/

.. [#GPL-COMPAT] GPL-compatible free software licenses,
   https://www.gnu.org/licenses/license-list.en.html#GPLCompatibleLicenses

.. [#PROJECTS] Licensing of Gentoo projects,
   https://wiki.gentoo.org/wiki/Project:Licenses/Licensing_of_Gentoo_projects

.. [#OSDL-DCO] Developer's Certificate of Origin 1.1,
   https://web.archive.org/web/20060524185355/http://www.osdlab.org/newsroom/press_releases/2004/2004_05_24_dco.html

.. [#FLA] FSFe Legal: Fiduciary Licence Agreement (FLA),
   https://fsfe.org/activities/ftf/fla.en.html

.. [#GFLA] Gentoo Fiduciary License Agreement,
   https://dev.gentoo.org/~rich0/fla.pdf


Copyright
=========

This work is licensed under the Creative Commons
Attribution-ShareAlike 3.0 Unported License.  To view a copy of this
license, visit http://creativecommons.org/licenses/by-sa/3.0/.
