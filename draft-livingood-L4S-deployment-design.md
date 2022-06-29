---
###
# Internet-Draft Markdown Template
#
# Rename this file from draft-todo-yourname-protocol.md to get started.
# Draft name format is "draft-<yourname>-<workgroup>-<name>.md".
#
# For initial setup, you only need to edit the first block of fields.
# Only "title" needs to be changed; delete "abbrev" if your title is short.
# Any other content can be edited, but be careful not to introduce errors.
# Some fields will be set automatically during setup if they are unchanged.
#
# Don't include "-00" or "-latest" in the filename.
# Labels in the form draft-<yourname>-<workgroup>-<name>-latest are used by
# the tools to refer to the current version; see "docname" for example.
#
# This template uses kramdown-rfc: https://github.com/cabo/kramdown-rfc
# You can replace the entire file if you prefer a different format.
# Change the file extension to match the format (.xml for XML, etc...)
#
###
title: "L4S Deployment Design Recommendations"
abbrev: "L4S Deployment Design"
category: info

docname: draft-todo-yourname-protocol-latest
submissiontype: IETF  
number: 
date: 2022-07-11
consensus: true
v: 3
area: TSV
workgroup: TSV Area Working Group
keyword:
 - latency
 - buffer bloat
 - L4S
 - low latency
venue:
  group: TSVWG
  type: Working Group
  mail: tsvwg@ietf.org
  arch: https://datatracker.ietf.org/wg/tsvwg
  github: jlivingood/L4S-Deployment-Design
  latest: https://github.com/jlivingood/L4S-Deployment-Design

author:
 -
    fullname: Jason Livingood
    organization: Comcast
    email: jason_livingood@comcast.com

normative: 

informative: 

--- abstract

TODO Abstract

--- middle

# Introduction

The IETF's Transport Area Working Group (TSVWG) has finalized experimental RFCs for Low Latency, Low Loss, Scalable Throughput (L4S) (INCL REFS HERE). These documents do a good job of describing the L4S architecture and protocol but as is normal for many such standards, especially those in experimental status, certain design decisions are ultimately left to implementers. 
 
 This document explores the potential implications of key deployment design decisions and makes recommendations for those decisions. 

# Network Neutrality Overview
 
TODO NN (INCL THAT DUAL QUEUE DOES NOT CREATE A FAST LANE)
 
# Implications of Deployment Design Decisions
 
TODO TEXT (INCL REF TO TUSSLE PAPER)
 
# Recommended Deployment Design Decisions
 
TODO TEXT
 
# Security Considerations

This document contains no particular security considerations. 
 
# Privacy Considerations

This document contains no particular security considerations. 

# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
