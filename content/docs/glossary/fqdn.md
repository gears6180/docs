--
seo:
  title: Fully Qualified Domain Name (FQDN)
  description: Definition of a fully qualified domain name as it relates to SendGrid.
  keywords: fqdn, fully qualified, dns, hostname, fully qualified domain, pqdn, tld
title: Fully Qualified Domain Name (FQDN)
group: glossary
weight: 0
layout: page
navigation:
  show: true
---

A Fully Qualified Domain Name (FQDN) is the complete domain name for a specific location in the Domain Name System (DNS) hierarchy. This is sometimes referred to as the absolute domain name.

The hierarchy can be broken down into a few parts:

- Top-Level Domain (TLD), such as .edu or .com
- Partially Qualified Domain Name (PQDN) or domain name, such as example.com
- Fully Qualified Domain Name (FQDN) or host name, such as mail.example.com

The format of FQDN includes all hierarchical parts, usually [hostname].[domainname].[tld]. A mail server, for example with SendGrid, could be specified by an FQDN such as `mx.sendgrid.net` as this provides the complete domain for a specific mail server. When connecting to a host the specification of a FQDN allows for the DNS to resolve the hostname to its specific IP in order to verify the connection and successfully send mail.
