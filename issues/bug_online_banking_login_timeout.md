# [Bug] Online Banking Portal Times Out During Login

**Labels**: `bug`, `support`, `banking`, `priority-high`

**Summary**: Users are unable to access the bank login dashboard due to repeated session timeout errors.

**OS**: Windows 10, macOS Sonoma  
**Browsers**: Chrome 120, Safari 17.3  

**Steps to Reproduce**:
1. Visit [https://www.bankofbaroda.in](https://feba.bobibanking.com/corp/AuthenticationController?FORMSGROUP_ID__=AuthenticationFG&__START_TRAN_FLAG__=Y&FG_BUTTONS__=LOAD&ACTION.LOAD=Y&AuthenticationFG.LOGIN_FLAG=1&BANK_ID=012)
2. Enter user ID and password
3. Press Login

**Expected**: Redirect to dashboard or 2FA  
**Actual**: Loading screen followed by “Session expired. Please try again.”

**User Sentiment**:
> “I can’t access my bank account for 3 days. This is urgent — please fix ASAP.”

**Temporary Workaround**: Works via mobile browser in incognito mode (Safari only)
