# Summary: Online Banking Login Session Timeout Issue

**Issue**: Users across desktop browsers are unable to log into the banking portal. Login attempts time out and redirect to error screen.

**Reports**: 12 tickets in 48 hours; reproducible across Chrome and Safari

**Reproduction**: Confirmed issue on latest Chrome (Win10) and Safari (macOS Sonoma)

**Hypothesis**:
- Session management token expiring prematurely
- Possible conflict with browser extensions or stale cookies

**Suggested Next Steps**:
- Dev: Check session token lifespan and header/cookie handling
- UX: Display clearer error message if timeout occurs
- Support: Update help page with workaround (Safari incognito mode)

**Priority**: High
