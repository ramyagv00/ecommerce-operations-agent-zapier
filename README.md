# E-Commerce Operations Agent

## Overview

An AI-powered Operations Agent built in Zapier that monitors checkout events and determines whether incidents should be logged or escalated.

## Business Problem

E-commerce teams receive hundreds of checkout events every day.

Manual review is slow and inconsistent.

## Solution

The agent:

- Reads checkout events from Google Sheets
- Evaluates severity using baseline metrics
- Produces exactly one output:
  - ALERT
  - LOG
- Sends decision via webhook
- Updates event status

## Tech Stack

- Zapier
- OpenAI
- Google Sheets
- Webhooks

## Architecture

See architecture folder.

## Screenshots

See screenshots folder.
