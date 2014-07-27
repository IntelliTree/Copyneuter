Copyneuter
==========

Best-effort castration of both copyright and copyleft


### Purpose

To develop a simple set of software development agreements which promote 
open-source but without the "poison pill" of so-called copyleft licenses
such as the GPL.

Copyneuter will not itself be a software license, but a practical agreement
to establish in advance //permissive// licenses which will automatically apply
to content/code created for a new project, such as between a customer and
a software development vendor or subcontractor.

The reason this is needed at all is because of copyright law which 
establishes onerous default powers to authors, even when someone else is
paying them to create the content. This is a problem which needs to be
addressed. The goal of Copyneuter is simply to fix this in a manner which
is equally fair to all parties.

General terms:

  * Copyright on the content remains with the original vendor/author
  * ...but is automatically licensed to the customer under a permissive license
    such as MIT/BSD/Artistic
  * Vendor/customer are free to decide on a case-by-case basis if the license 
    will be //exclusive// to the customer or public/open-source. The default 
    should be exclusive, however, there should be a simple mechanism to make
    open-source:
      * The customer may declare it should be open-source (which should already 
        be implied by their permissive license) 
      * The vendor declaring in advance their intent to open-source a specific 
        component and the customer not refusing when given a reasonable 
        opportunity to do so.
  * For all derived works, included libraries, etc, for which the vendor is //not//
    the copyright holder, whatever is the most permissive license granted to the
    vendor shall be passed on to the customer

The idea is that this agreement can be used to avoid the silly and time-consuming
negotiation which is created simply by the vacuum created by having no agreement
at all. From the standpoint of the vendor, no agreement is already slanted in 
their favor, but this will create the need for the customer to propose an 
agreement which, if they realize the copyright issue in the first place, is likely
to be just as onerously slanted in the other direction (al a iTunes Terms and 
Conditions). The goal is to stop the lawyers before they ever get involved. The
vendor can mitigate the high transaction cost by just proactively agreeing to
be reasonable.

This is still just preliminary brainstorming... comments/feedback welcome


