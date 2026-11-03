# Changelog

## 1.0.0
- First release.

## 1.0.1
- Fix tool schema for Bedrock.

## 1.1.0
- AWS keys can now be rotated or set per home from the portal; homes pick up changes automatically.

## 1.2.0
- New: choose how Buddy works with you, "Buddi-and-I" (Buddy shows its plan and waits for your OK) or "Only-Buddy" (Buddy acts straight away).
- New: voice control in the web chat ("Hey Buddy"), with spoken replies.
- The agent code now ships compiled (no source files on the device).

## 1.2.1
- Keeps the tool server running between messages (faster replies).
- Logs a TIMING line per message (model calls and tool calls) to help find slow steps.

## 1.3.0
- New: per-person **Buddy Memory** and **Buddy Preference** switches (Account page). Memory Off makes Buddy noticeably faster.
- New: care-home mode. High-risk actions (locks, alarms, restarts, automations) always ask for confirmation first, and what Buddy did is reported to the care dashboard.
