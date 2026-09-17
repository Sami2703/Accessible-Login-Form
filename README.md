# Accessible-Login-Form
Login Form with Email, Password, Remember Me, Login, Forgot Password | Used label, input, button

Build this yourself first:

┌─────────────────────────────┐
│          Login              │
│                             │
│ Email                       │
│ [_______________________]   │
│                             │
│ Password                    │
│ [_______________________]   │
│                             │
│ ☑ Remember Me               │
│                             │
│ [        Login          ]   │
│                             │
│ Forgot Password?            │
└─────────────────────────────┘

⭐ accessibility checklist
Before considering the exercise complete, check:

✅ Every input has a label
✅ label's "for" matches input's "id"
✅ Inputs have meaningful "name"
✅ Correct input types are used
✅ required is used where appropriate
✅ autocomplete is provided
✅ Real button is used for Login
✅ Real link is used for navigation
✅ Form works with keyboard
✅ No clickable divs


🎤 Final 60-second interview answer
If an interviewer asks:
"How would you make a login form accessible?"

Say:
"I would use semantic HTML and associate every input with a proper label using for and id. I'd use appropriate input types like email and password, add required and autocomplete where appropriate, and use a semantic button for submission. I'd also make sure the form is keyboard accessible and use ARIA only when native HTML doesn't provide enough information. For validation messages or additional instructions, I can use aria-describedby to associate that information with the relevant field."
