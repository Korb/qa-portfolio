# Security Policy

## Wait, Security Policy for a Portfolio?

Yes, I know this seems odd. There's no code to exploit here, no servers to hack, no databases to inject into.

But "security" in the context of a professional portfolio means something different: protecting sensitive information that might accidentally appear in case studies, and ensuring the integrity of the work presented.

## What Actually Needs Protecting

### 1. Commercial Confidentiality

**Risk**: Accidentally including internal company data, project codenames, unreleased features, or proprietary processes.

**Example**: "Company X's internal bug tracker issue #CONF-12345 revealed..."

**If you find this**: Please report it immediately. Companies trust me with sensitive information; maintaining that trust is critical.

### 2. Personal Data

**Risk**: Including real names, email addresses, or identifying information of colleagues/users without consent.

**Example**: Screenshots containing usernames, forum posts with real names, or test data with actual email addresses.

**If you find this**: Let me know. Privacy matters, and I should anonymize or blur such data.

### 3. Misattribution

**Risk**: Accidentally claiming credit for work done by others, or failing to properly attribute collaborative efforts.

**Example**: "I implemented this feature" when it was actually a team effort or someone else's idea.

**If you find this**: Point it out. Professional integrity requires accurate credit assignment.

### 4. Broken External References

**Risk**: Links to internal bug trackers, private forums, or confidential documentation that shouldn't be public.

**Example**: Link to `https://internal.company.com/ticket/12345` that reveals company infrastructure.

**If you find this**: Flag it. These links should either be removed or replaced with screenshots/descriptions.

### 5. Outdated or Inaccurate Information

**Risk**: Case studies that no longer accurately represent current product state, or statistics that have changed.

**Example**: "As of 2024, feature X works this way..." when it's been completely redesigned.

**Note**: This is lower severity, but still worth reporting if you notice significant inaccuracies.

## How to Report Security Issues

### For Actual Sensitive Data (High Priority)

**Contact me directly:**
- **LinkedIn**: [https://www.linkedin.com/in/gallem/](https://www.linkedin.com/in/gallem/) (DM)
- **Email**: Available on LinkedIn profile

**Please include:**
- Link to the specific file/line/section
- Description of what sensitive data is exposed
- (Optional) Suggested redaction/fix

**Response time**: I'll acknowledge within 48 hours and fix within 1 week.

### For Minor Issues (Lower Priority)

**Open a GitHub Issue:**
- Broken links → [Open Issue](https://github.com/Korb/qa-portfolio/issues)
- Attribution concerns → [Open Issue](https://github.com/Korb/qa-portfolio/issues)
- Factual inaccuracies → [Open Issue](https://github.com/Korb/qa-portfolio/issues)

Or just open a Pull Request with the fix. I'll review and merge if appropriate.

## What's NOT a Security Issue

### These are fine (please don't report):

- **Public forum links**: Links to bugs.telegram.org, PDF-XChange forum, GitHub issues—these are all public
- **My own personal data**: My name, LinkedIn, GitHub profile, location—all intentionally public
- **General QA findings**: Bug reports, feature requests, usability issues—the entire point of this portfolio
- **Typos**: Just open a PR, no need for security disclosure process

### Gray areas:

- **Company names**: Generally fine (I worked there publicly), unless paired with confidential details
- **Product names**: Fine for released products, problematic for unreleased/confidential projects
- **Statistics**: Public data (e.g., "2,500+ issues filed") is fine. This is open data, verified through statistics interfaces, API requests, or manual verification. If you would like [to contribute](https://github.com/Korb/qa-portfolio?tab=contributing-ov-file) to this repository, I will provide you with all information support to confirm the information stated.

**When in doubt**: Ask yourself, "Would this harm the company, individual, or my professional reputation if it became widely known?" If yes → report. If no → probably fine, but you can still ask.

## Commitment

I take professional confidentiality seriously. This portfolio exists to demonstrate QA skills, not to expose sensitive information.

If you report a legitimate security concern:
1. I'll fix it promptly
2. I'll credit you in the commit (if you want)
3. I'll be genuinely grateful—protecting this portfolio's integrity protects my career

## Questions?

**"Why not just use private repository?"**  
Because the entire point is demonstrating public-facing QA work. Transparency is the feature, not the bug.

**"What if I worked at one of these companies and object to inclusion?"**  
Contact me directly. If there's a legitimate concern about confidentiality or misrepresentation, I'll address it immediately.

**"Is this overkill for a portfolio?"**  
Maybe. But demonstrating that I understand security policies—even in unusual contexts—is itself a portfolio piece. Meta, right?

---

**Last updated**: January 2026  
**Policy version**: 1.0
