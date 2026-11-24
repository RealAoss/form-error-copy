---
name: form-error-copy
description: Write accessible recovery instructions for form validation errors when given field labels, failure states, and validation rules.
---

# Form Error Copy

Map each error to its visible field label and to the rule actually enforced. Distinguish a missing answer, a format mismatch, an out-of-range value and a server failure. Only instruct users to edit their answer when editing it could resolve the failure.

For each supplied state, return the field, trigger, inline message and a manual check. In the message, tell the user what to enter next. Give a valid example when format is the obstacle. Preserve locale, allowed units and boundary inclusivity. If the format is unknown, request the rule before supplying an example.

For multi-field submissions, draft a short summary with the affected field labels so each item can link to its control. Keep inline errors meaningful when read with their field label. If asked to review accessibility, identify checks that require the rendered form, including keyboard focus, accessible descriptions and announcement timing.

For account lookup and recovery, preserve any intentional ambiguity about account existence. Omit submitted secrets from all copy.
