# Social Account Recovery Assistant

AI-powered **digital account recovery guide + appeal automation** concept focused on safe, legitimate account recovery workflows.

## Problem
Users frequently struggle with:
- banned/disabled accounts
- hacked or stolen accounts
- login/access issues
- identity verification blocks
- unclear support processes

This product helps users understand and complete official recovery steps, while generating high-quality appeal drafts.

## Product Positioning
This is a:
- ✅ recovery guidance tool
- ✅ appeal writing assistant
- ✅ support process helper

This is **not** a:
- ❌ hacking tool
- ❌ bypass/exploit tool

## Core User Flow
1. **Platform selection** (Instagram, Facebook, WhatsApp, Snapchat, X)
2. **Problem selection** (ban, hacked account, login issue, etc.)
3. **Smart minimal form** (only required user fields)
4. **AI appeal generation** (personalized, polite, platform-aware)
5. **One-click mail compose** (prefilled email in user’s own mail client)
6. **Official recovery guide** (links + steps)
7. **Recovery tracking** (sent, waiting, reply, resolved)

## MVP Feature Set
- Platform recovery engine (rules + links + templates)
- AI email personalization with safe variation
- Minimal-data collection with clear privacy notice
- Recovery guides and security recommendations
- Appeal history view
- Multi-language baseline (English + Hindi; Gujarati as extension)

## Security & Trust Requirements
- HTTPS only
- no plaintext storage of sensitive fields
- data minimization by default
- optional local-only processing mode
- auto-delete generated case data after completion
- strict privacy disclosure and consent screens

## Suggested MVP Architecture
- **Frontend**: React web app (or Android client)
- **Backend**: Python Flask API
- **AI layer**: LLM-backed appeal generation service
- **Recovery knowledge**: JSON or small database

### Data Flow
`User Input -> Validation -> Appeal Generation -> Mail Client Prefill -> Data Deletion`

## Compliance and Risk Controls
- Explicit legal disclaimer:
  > We assist in the account recovery process only. We do not guarantee account recovery.
- Abuse prevention:
  - rate limits
  - anomaly checks
  - attempt throttling
  - template randomization within safe bounds
- Continuous maintenance plan for platform policy changes.

## 4-Week MVP Delivery Plan
### Week 1
- UX wireframes
- platform + issue taxonomy
- base navigation flow

### Week 2
- form engine
- template generation pipeline
- localization-ready string structure

### Week 3
- mail prefill integration
- official recovery guides module
- tracking status model

### Week 4
- QA and security checks
- launch documentation
- initial deployment

## Next Milestones (Post-MVP)
- guided visual tutorials
- in-app assistant chat
- business account workflows
- browser extension
- analytics-driven optimization
