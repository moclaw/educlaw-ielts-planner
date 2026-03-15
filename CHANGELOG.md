# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2026-03-15

### Added
- Initial release of EduClaw IELTS Study Planner skill
- 4-step workflow: Schedule Preferences → Research & Plan → Calendar → Documentation
- Bilingual support (English & Vietnamese) with automatic language detection
- Google Calendar integration via gcalcli with unique event descriptions per session
- Dynamic timezone detection (never hardcoded)
- Google Sheet progress tracker (4 tabs: Session Log, Vocabulary Bank, Materials Library, Weekly Summary)
- Discord notifications for calendar conflicts, study reminders, and progress reports
- 5 cron job templates (daily prep, weekly report, material update, calendar watcher, conflict check)
- 4-month IELTS roadmap template (Band 6.0 → 7.5+) in 4 phases
- Comprehensive guardrails: no auto-scheduling, no auto-conflict resolution, approval required
- Detailed calendar event format with vocabulary, lesson plans, materials, exercises, self-check
- Quality enforcement: 100% unique descriptions across all sessions
- Channel-aware output formatting (Discord, TUI, CLI, Cron)
