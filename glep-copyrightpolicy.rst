---
GLEP: XXX
Title: Copyright Policy
Author: Richard Freeman <rich0@gentoo.org>,
        Alice Ferrazzi <alicef@gentoo.org>,
        Ulrich Müller <ulm@gentoo.org>
Type: Informational
Status: Draft
Version: 1
Created: 2013-04-23
Last-Modified: 2018-02-10
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

In the past Gentoo developers signed contributor licensing agreements
formally assigning copyright to the Gentoo Foundation, and copyright headers
in individual files reflected this.  Then at some point in time these formal
agreements no longer were being signed, but the headers remained, and were
enshirned in policy.  This led to a situation where copyright ownership
might be ambiguous.

Also, the general policy to have Gentoo Foundation copyright notices
caused an issue when Gentoo developers forked another project and hosted
the fork on Gentoo infrastructure.  To comply with the previous policy
the copyright notices were modified, which caused concerns with the 
project the files were forked from.  Our previous policy completely
neglected the possibility that Gentoo might want to host files that 
were not created internally.

Finally, since the early days of Gentoo new ideas around copyright
licensing have become more popular, such as the FSFe's Fiduciary
License Agreement, which takes a copyleft approach to copyright licensing,
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
contract and the FLA).

Copyright is assigned to the Foundation by electronically signing the
Gentoo Fiduciary License Agreement (FLA) [#FLA]_.

The agreement may be signed BY **TODO...**  If the scope of the signed
agreement included future contributions, the contributor may document
their wish to stop assigning copyright by **TODO...**

A list of those who have signed this agreement and the scope of their
assignments may be found at **LINK**.  This list may be useful when
attributing copyright.


Rationale
=========


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

.. [#FLA] Gentoo Fiduciary License Agreement,
   https://dev.gentoo.org/~rich0/fla.pdf


Copyright
=========

This work is licensed under the Creative Commons
Attribution-ShareAlike 3.0 Unported License.  To view a copy of this
license, visit http://creativecommons.org/licenses/by-sa/3.0/.
