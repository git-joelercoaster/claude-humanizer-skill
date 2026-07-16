# Genre Profile: UX Copy & Microcopy

Error messages. Onboarding flows. Help text. Button labels. Empty states. Confirmation dialogs. Instruction text. CTAs.

## The Goal

**Task-first. User-focused. Minimal. The text should be invisible.**

UX copy isn't marketing. It's a tool. The best UX copy gets out of the way and lets users do what they need to do.

## What Changes

### DO Strip

- Marketing language (transformative, revolutionary, empower)
- Fake friendliness that masks poor UX
- Excessive personality (emoji, exclamation points, puns)
- Jargon that users don't understand
- Multiple questions in succession
- Anything that makes users *read* instead of *act*
- Apologies that don't fix the problem
- Vague language (try again, something went wrong)

### DO NOT Strip

- Warmth (you can be friendly without being fake)
- Personality, if it serves clarity (e.g., Mailchimp's tone is casual because it fits their brand, AND it makes copy clearer)
- Emoji, if it clarifies (a single ✓ on a success state, or 🔒 on a password field, is clear)
- Conversational tone (users respond better to "We need..." than "A valid email address is required")
- Specific guidance (tell users exactly what to do)
- Humor, if it serves the task (never pure entertainment)

## Signs of AI in UX Copy

**Problem areas:**
- "Welcome to our innovative platform designed to transform your experience" ← delete this entirely
- "Please enter a valid email address to seamlessly continue" ← "Email address required"
- "Congratulations! You've successfully created an account, marking a pivotal moment in your journey with us" ← "Account created"
- "Something unexpected occurred" ← what exactly failed?
- Buttons labeled "Submit Your Information" ← "Continue" or "Save"
- Help text that explains the system instead of helping the user
- Multiple sentences when one would do
- Cutesy language that delays task completion

**Good UX copy:**
- Tells the user what to do
- Explains *why* if needed
- Gets out of the way
- Specific, not vague
- No more than one sentence (usually)
- Assumes the user knows what they want

## The UX Principle

Every word a user has to read is a word that delays task completion. Good UX copy is invisible. Users notice only when something's confusing.

AI tries to make UX copy *visible* — to impress, to reassure, to establish a relationship. Users don't care. They want to complete the task.

## Common UX AI Mistakes

**Mistake 1: Marketing in the UI**
> "Welcome! You're about to embark on an exciting journey to unlock your full potential with our transformative platform."

**Fix:**
> [Delete entirely. Get to the form.]

---

**Mistake 2: Vague error**
> "Something went wrong. Please try again."

**Fix:**
> "Your password must be at least 8 characters."

or

> "This email is already registered. Sign in instead?"

---

**Mistake 3: Explaining the system instead of helping**
> "Our advanced verification algorithm requires at least 24 hours to process your request in order to optimize system stability and security."

**Fix:**
> "We'll verify your identity in 1 business day."

---

**Mistake 4: Excessive friendliness**
> "Whoopsie! 🙈 Something didn't work out like we planned. Our team is probably sleeping now, but try again when the sun comes up! ☀️"

**Fix:**
> "Error. Our servers are down. We'll be back in 30 minutes."

(or, if you know the issue:)

> "Your file is too large (max 25MB). Try compressing it."

---

**Mistake 5: Fake apology**
> "We sincerely apologize for the inconvenience this error has caused. We are deeply committed to resolving this issue and ensuring your complete satisfaction."

**Fix:**
> "This payment method doesn't work. Try another card."

(If you actually messed up:)

> "Sorry, we deleted your data by mistake. It's being restored now. Should be back within 2 hours."

---

**Mistake 6: Button labels that don't say what they do**
> "Let's Go" / "Submit Your Preference" / "Proceed"

**Fix:**
> "Create Account" / "Save Changes" / "Confirm Order"

(Use the verb that describes the action.)

---

**Mistake 7: Help text that's too long**
> "In order to successfully log in to your account, you will need to enter your username (or the email address you used when registering) along with your password in the fields below. This password is case-sensitive and must contain at least 8 characters, including one number and one special character."

**Fix:**
> "Email or username (case-sensitive)"
> "Password (8+ characters, 1 number, 1 symbol)"

---

## UX Copy Hierarchy

**Priority 1 (always clear):**
- Error messages (what failed? why? what now?)
- Confirmations (what did you just do?)
- Required actions (what must the user do?)

**Priority 2 (be clear, can be brief):**
- Empty states (what should they do now?)
- Helper text (why are we asking?)
- Warnings (what will happen?)

**Priority 3 (can be personality):**
- Success states (affirm the win, briefly)
- Onboarding (get them to the product, fast)
- CTAs (be enthusiastic if the action is good)

**Priority 4 (minimize):**
- Explanations of system behavior
- Apologies (fix the problem first)
- Marketing messages

## Checkpoints Before Launch

- [ ] Can a user understand what to do in 3 seconds?
- [ ] If there's an error, is it specific (not "Something went wrong")?
- [ ] Are button labels verbs that describe the action?
- [ ] Is the tone consistent (not cartoony in one place, robotic in another)?
- [ ] Did I avoid: innovative, transform, empower, unlock, journey, seamless, cutting-edge?
- [ ] Did I remove marketing language?
- [ ] Is there anything here users don't need to read?
- [ ] Would my 70-year-old mom understand this?
- [ ] Does the tone match the situation (serious error → serious tone, onboarding → lighter)?

## Examples

### Onboarding Email

**Before (AI):**
> Welcome to the future! 🚀
>
> You're about to embark on a transformative journey with our innovative platform. We're thrilled to have you join our community of forward-thinking professionals.
>
> Get started by exploring these exciting features:
> - Seamlessly integrate your data ✨
> - Unlock powerful insights 💡
> - Empower your team to drive impact 🔥
>
> Let's transform your business together!

**After (Human):**
> Hi [Name],
>
> Your account is ready. Start here:
> 1. Add your data (5 min) — connect your database
> 2. Build your first report (10 min) — drag & drop interface
> 3. Share with your team — invite up to 5 people on free tier
>
> Stuck? See the quick start guide or email help@example.com

---

### Error Message

**Before (AI):**
> An unexpected error has occurred. We sincerely apologize for any inconvenience this may cause. Please try again later or contact our support team if the problem persists.

**After (Human):**
> We couldn't process your payment. Try these:
> - Refresh and try again
> - Use a different card
> - Call us: 555-1234 (we'll help, 5 min)

---

### Empty State

**Before (AI):**
> Congratulations on creating your account! Your journey toward success has begun. To unlock the full potential of our innovative platform, begin by creating your first project. This exciting step will empower you to transform your workflow and achieve unprecedented productivity.

**After (Human):**
> No projects yet. Create one to get started. (Takes 2 minutes)

---

### Confirmation Dialog

**Before (AI):**
> Are you absolutely certain you wish to permanently delete this item? Please note that this action cannot be undone and will result in the irreversible removal of all associated data. We recommend proceeding with caution.

**After (Human):**
> Delete this project? This can't be undone.
> [Cancel] [Delete]

---

### Help Text

**Before (AI):**
> Our advanced algorithm requires a minimum of three characters to effectively search your database and provide you with optimal results.

**After (Human):**
> Search requires 3+ characters

---

## Voice Calibration for Product Teams

If a product has an established UX voice:

Look for:
- **Formality level** (is it conversational? Professional? Between?)
- **Personality** (present? Absent? How much?)
- **Tone in errors** (apologetic? Practical? Friendly?)
- **Emoji usage** (none? Selective? Everywhere?)
- **Sentence length** (fragments? Full sentences? Mix?)
- **Assumptions about user knowledge** (technical? Non-technical?)

**Example calibration:**
> "This product's voice: conversational but professional, light personality (not cartoonish), practical in errors (no false apologies), emoji used sparingly for clarity, mix of fragments and sentences, assumes users are non-technical."

Match this in UX copy edits.

---

## When UX Copy Can Be Longer

Some contexts warrant longer UX copy:

- **Irreversible actions** (deleting, shutting down, major changes) — explain consequences
- **Complex concepts** (if the feature is truly complex, explain briefly)
- **Legal/compliance** (privacy, terms, billing) — necessary evil
- **First-time setup** (onboarding can spend more words because it's new)

But even these should be as short as possible. Test with real users.

---

## The UX Writing Virtue

Great UX copy is invisible. Users never think about it. They just complete their task.

The worst UX copy makes you *read* instead of *do*.

AI makes users read. Humans make them act.
