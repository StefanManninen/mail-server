# No Bullshit Mailserver

If you cannot adapt this to your environment,
you probably should not run your own mailserver.

A working self-hosted mailserver setup based on:

- Postfix
- Dovecot
- Rspamd
- OpenDKIM
- Fail2Ban
- Unbound
- Nginx

This is not a commercial product. This is not a universal guide. This is a
working setup I use myself.

Use it, modify it, or ignore it.

## Installation

No installation instructions are provided.

If you cannot install and wire these components together,
you should not run your own mailserver.

## Goal

Simple, predictable and observable mail hosting.

No panels.  
No magic.  
No external relay dependency.

## What this setup is for

- personal domains
- small-scale hosting
- people who want control
- people who are willing to read logs

## What this setup is not for

- mass mailing
- newsletter delivery
- people who want one-click hosting
- people who do not want to understand email

## Philosophy

Mailservers are not hard because of the software.  
They are hard because of DNS, reputation, abuse handling and hidden assumptions.

This setup focuses on:

- clean DNS
- SPF / DKIM / DMARC
- spam filtering
- sane firewall rules
- observable logs
- minimal moving parts

## Status

Works for me.

Mail-tester score: 10/10

This does not fix bad IP reputation.
Email delivery is mostly DNS and reputation.
Not configuration.

## Support

No support is promised.  
Issues may be ignored.  
Pull requests may be ignored.
