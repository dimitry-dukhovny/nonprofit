#####################################
Doing business with the US government
#####################################

* Government funding comes in the form of **contracts** and **grants**.  The acquisition cycle for these is similar.

* The US government directly funds more than a third of the aggregate non-profit / non-government organization budget.

Should you work with the US
===========================

* In nations with strict foreign agent registration rules, consider long-term political risk of being associated with US funding.

  * Solutions to the conundrum of needing US support and tying an NGO to it is to include US funding in a basket of foreign and treaty organization support.

.. note:: The converse is also true.  The business plan must dictate a decision on the rollback of US involvement if any part of the basket of support changes.

* Who you are to the US Government

  * NGO

  * In-country partner

  * Subject matter expert

USAID
=====

* USAID provides food, clean water, medical assistance, and education all over the world.

* https://www.usaid.gov/work-usaid/get-grant-or-contract/trainings-how-work-usaid

State Department
================

DOD
===

* PSYOP and Civil Affairs conducts assistance operations all over the world, particularly school construction and medical and veterinary assistance.


SAM registration
================

Prerequisites
+++++++++++++

* The human element

  * Ensure your POC is a US person

    * A US citizen or green-card holder, regardless of where they live

    * Consider favorable demographics...

      * woman-owned

      * disabled-owned

      * veteran-owned

      * minority-owned

  * Permission to do work in the US

    * Taxpayer identification numbre

    * Employment identification number

  * Free DUNS number

* Sizing government effort

  * Capacity planning

  * Decompose government mission

  * Gap analysis and bid analysis

    * We normally associate "bids" with commercial efforts, but application for grants are almost indistiguishable.

.. note:: Build audit and financial reporting into the earliest stages of the business plan.
..

Sam Timeline
++++++++++++

.. graphviz::

  digraph timeline {
    rankdir=LR
    node [ shape=note ]

    invis0 [ shape=point, fontcolor=transparent ]
    invis1 [ shape=point, fontcolor=transparent ]
    taxstatus [ label="501(c)(3)\nstatus", shape=box ]
    EIN [ label = "employer\nor tax ID" ]
    DUNS [ label = "DUNS\nnumber" ]
    SAM_portal [ label="SAM\nportal", shape="box" ]
    SAM_account [ label="SAM\naccount" shape="component" ]

    invis0 -> invis1 [ color=orange, label="48 days" ]
    invis0 -> taxstatus [ color=transparent ]
    taxstatus -> EIN [ label="35 days", color=red ]
    taxstatus -> DUNS [ label="14 days", color=red ]
    DUNS -> SAM_portal [ color=blue ]
    EIN -> SAM_portal [ color=blue ]
    SAM_portal -> SAM_account [ label="14 days", color=red ]
    SAM_account -> invis1 [ color=transparent ]
  }
..

Solicitations
=============

* Much like the normal acquisition process, the partnering process begins with market research.

* Responding to US government queries before requirements are fixed

Request for Information (RFI)
  A call for organizations to share technical or other requested information before we issue a formal solicitation. The RFI is one way USAID explores ideas and plans for future projects in a particular area.

Pre-Solicitation Notice
  A notification that the Agency will be issuing a solicitation.

Sources Sought Notice
  A notice to determine the number of organizations interested in a possible funding opportunity, their level of experience and qualifications, and the suitability of an activity for a particular type of small business set-aside.

Draft Notice of Funding Opportunity (NOFO)
  A draft of the NOFO, released before the formal solicitation is announced;  its purpose is to receive feedback and input.

Draft Scope of Work
  A draft of the planned scope of work that enables organizations to provide feedback and to get a better understanding of a planned activity.

.. note:: Build each of these response types into the operations chapter of the business plan explicitly.  Rehearse each.
..

Getting funded
--------------

Request for Proposal (RFP)
  An official solicitation for acquisition awards (contracts) that tells you what the Agency requires for a specific project or activity and how it will evaluate bids. All RFPs are posted on SAM.gov.

Notice of Funding Opportunity (NOFO)
  An official solicitation for assistance awards (grants and cooperative agreements). All NOFOs are posted on Grants.gov.

Annual Program Statement (APS)
  A “call to action” released by USAID on Grants.gov, usually once a year, that outlines the need for a specific kind of program and encourages the submission of a wide range of concept papers.

Broad Agency Announcement (BAA)
  A competitive and collaborative research and development process used to seek innovative solutions to development challenges from public, private, for-profit, and nonprofit partners. 

