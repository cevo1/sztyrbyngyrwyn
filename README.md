# Sztyrbyngyrwyn

Private application using the Allegro REST API.

## Purpose

A personal, single-user tool that queries the Allegro REST API to monitor
public offer listings and prices for second-hand power tools. It is used for
private market research ahead of purchase and resale decisions.

The application does not resell, redistribute or publish Allegro data. It runs
locally on the owner's machine and is not offered to or used by other people.

## Scope of use

- Read-only queries against public offer listings
- Own offer and order management for the owner's Allegro account
- Requests are rate-limited and run on a schedule, not continuously

## Owner

Karol Gawerda

Contact: <add your email here>

## Technical

- Authorisation: OAuth 2.0
- User-Agent: `Sztyrbyngyrwyn/1.0.0 (https://github.com/cevo1/sztyrbyngyrwyn)`
