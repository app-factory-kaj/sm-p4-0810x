# sm-p4-0810x — PRD

## Problem Statement

People jotting down quick, short thoughts — a reminder, a snippet, a to-do — often reach for whatever is at hand (a chat to themselves, a sticky note, a random app) because there is no small, dedicated place to just add a note and see the notes they already have. The workaround costs them a scattered trail of notes across tools and no single list to check back against.

## Solution

A tiny note-keeping tool where a signed-in user can quickly add a short note and list the notes they have added, with nothing else to learn or configure. This is a post-fix smoke probe, intended to verify the pipeline is working after a fix rather than to grow into a full product.

## Actors

- **User** — a signed-in person who adds short notes and views the list of notes they have added.

## User Stories

1. As a User, I want to add a short note, so that I can capture a quick thought before I lose it.
2. As a User, I want to list my notes, so that I can see everything I have jotted down.

## Product Decisions

- Sign-in: every user signs in via SSO through Thunder, the platform IDP (org default).
- Notes are private per user — each user only sees and lists the notes they themselves added. *assumed*
- Notes are add-and-list only in this product — no editing or deleting a note. *assumed*

## Out of Scope

- Editing an existing note.
- Deleting a note.
- Sharing or publishing a note to other users.
- Organizing notes with tags, folders, or search.
- Rich text, attachments, or images in a note.

## Open Questions

None at this time.

## Further Notes

None.