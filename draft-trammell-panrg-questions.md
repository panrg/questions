---
title: Open Questions in Path Aware Networking
abbrev: PAN questions
docname: draft-trammell-panrg-questions-latest
date:
category: info

ipr: trust200902
area: Transport
workgroup: TAPS Working Group
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
  -
    ins: B. Trammell
    name: Brian Trammell
    org: ETH Zurich
    email: ietf@trammell.ch
    street: Gloriastrasse 35
    city: 8092 Zurich
    country: Switzerland

normative:

informative:


--- abstract

write me

--- middle

# Introduction to Path-Aware Networking

In the current Internet architecture, the network layer provides an
unverifiable, best-effort service: an application can assume that a packet
with a given destination address will eventually be forwarded toward that
destination, but little else. A transport layer protocol such as TCP can
provide reliability over this best-effort service, and a protocol above the
network layer such as IPsec AH {{!RFC4302}} or TLS {{!RFC5246}} can
authenticate the remote endpoint. However, no explicit information about the
path is available, and assumptions about that path sometimes do not hold,
sometimes with serious impacts on the application, as in the case with BGP
hijacking attacks.

By contrast, in a path-aware networking architecture, endpoints have the
ability to select or influence the path through the network used by any given
packet, and the network layer explicitly exposes information about the path or
paths available between two endpoints to those endpoints so that they can make
this selection. Path control at the packet level enables new transport
protocols that can leverage multipath connectivity even over a single
interface. 

# Questions

Realizing path-aware networking requires answers to a set of open research
questions. This document poses these questions, as a starting point for
discussions about how to realize path awareness in the Internet, and to direct
future research efforts within the Path Aware Networking Research Group.

## A Vocabulary of Path Properties

write me

## Discovery and Dissemination of Path Properties

write me

## Authentication and Trustworthiness of Path Properties

write me

## Supporting Path Selection

write me

## Authentication and Authorization of Path Selection

write me

## Interfaces for Path Awareness

write me

## Economics of Path Aware Internetworking

write me

# Acknowledgments

Many thanks to... write me

This work is partially supported by the European Commission under Horizon 2020
grant agreement no. 688421 Measurement and Architecture for a Middleboxed
Internet (MAMI), and by the Swiss State Secretariat for Education, Research, and
Innovation under contract no. 15.0268. This support does not imply endorsement.