# [Bug] Transaction Fails After 2FA Verification

**Labels**: `bug`, `banking`, `transaction`, `priority-high`

**Summary**: Users report that transactions fail after successful 2FA on the online banking portal.

**OS**: Windows 11  
**Browser**: Chrome 124  
**2FA Method**: OTP via SMS

**Steps to Reproduce**:
1. Log into online banking
2. Initiate NEFT transfer
3. Enter OTP received via SMS
4. Press Confirm

**Expected**: Confirmation of transaction success  
**Actual**: Error message “Transaction failed. Please try again.”

**Reported Impact**:
> “Money deducted from account but not credited to recipient. Very stressful.”

**Temporary Fix**: None confirmed. Retry sometimes works after logging out and in again.
