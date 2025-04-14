# BPM
**Onboarding proess workflow**

<b>
<img src=(https://i.imgur.com/iK7wVHS.jpeg)> 
</b>

1. Welcome & Entry
 - Includes language selection for accessibility.

2. Link Account

- Existing Users:
  - Direct to "Add Credentials" (email/username + password).
  - "Forget Password" flow if login fails.

3. New Users:
  - Multi-step verification: Email verification → Triggers OTP confirmation.
  - Password creation with validation checks (e.g., retry if invalid).
  - KYC document upload (e.g., ID, proof of address).
  - Security & Compliance: Biometric verification (fingerprint) for enhanced security.

4. Terms & Conditions acceptance mandatory for progression.

5. Fallback options for failed verification (e.g., "Retry/contact support").

**Post-Verification**
  - Optional tutorial (user can "Skip Tutorial" to proceed to the dashboard).
  - Ends at Dashboard, the app’s main interface.

**Decision Points & Error Handling:** Conditional checks at every critical step (e.g., "Valid Password?", "Email Verified?").

**Retry mechanisms for failed attempts (e.g., OTP, KYC document rejection).**

**Support pathways (e.g., visit branch/contact support) for unresolved issues.**

**User-Centric Features:** Flexibility to link existing accounts or create new ones.

**Skip options (tutorial, highlights) to reduce friction.**

**Clear error messaging and guided retries to enhance usability.**
