# Confluence Weekly Digest Bot

> Automated weekly knowledge digest powered by Make, Confluence API, and Claude.

## Background

This tool was built as part of a self-initiated portfolio project to demonstrate
real world AI workflow automation for agile teams. Build #2 in a growing suite
of automation tools that eliminate repetitive manual work from agile delivery
workflows.

The Confluence Weekly Digest Bot runs every Monday morning with zero human
input. No one has to remember to run it. No one has to write it. It just
happens — and the team starts every week fully informed.

I am a Human + AI Operator specializing in workflow automation for agile teams
and project managers. Currently accepting pilot clients at reduced rates. Full
case study and live demo available at jleighsmithconsulting.netlify.app

## What It Does

Runs every Monday morning automatically with zero human input. Connects to
Confluence via API, pulls all pages updated in the last seven days, sends the
content to Claude AI, and delivers a clean professional weekly digest to Google
Drive before the team starts work.

## The Problem It Solves

Teams that use Confluence lose time every week to information overload and
missed updates. Important decisions get buried. Team members stay out of sync.
Knowledge management becomes a liability instead of an asset.

## How It Works

1. Make schedule trigger fires every Monday morning at 8am automatically
2. Make connects to the Confluence API using Basic Auth and pulls all recently updated pages
3. Claude reads the page titles and content and generates a formatted weekly digest
4. Digest lands automatically in a designated Google Drive folder

## The Output

The generated digest includes:

- Weekly activity summary
- Pages updated this week with descriptions of what each page covers
- Key decisions and action items surfaced automatically
- Suggested owners and due dates
- Professional format ready to share with the team

## Stack

- Make — scheduled workflow orchestration
- Confluence API — page data retrieval
- Claude API (claude-sonnet-4-6) — digest generation
- Google Docs — digest delivery

## Sample Output

[Watch Live Demo]: https://drive.google.com/file/d/13PdKZ1naCJcJy23faX65o_now7qdLYRE/view?usp=drive_link

Full case study available at [jleighsmithconsulting.netlify.app](https://jleighsmithconsulting.netlify.app)

## Key Metrics

- Runs automatically every Monday — zero human input required
- Covers all pages updated in the last 7 days
- Delivers before the team starts work
- Replaces manual Confluence monitoring entirely

## About

Built by J. Leigh Smith — AI Workflow Automation Specialist

- Portfolio: https://jleighsmithconsulting.netlify.app
- Email: jernansmith@outlook.com
- LinkedIn: https://www.linkedin.com/in/jernansmith/

*Self-initiated portfolio project. Currently accepting pilot clients at reduced rates.*
