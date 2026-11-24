# Form Error Copy

Turn vague form errors into actionable instructions. Copy the instructions in [SKILL.md](SKILL.md) into ChatGPT or Claude, then provide the field labels, failing inputs, supported locales and actual validation rules.

## Example

Input: the field is “Number of guests”. The booking accepts whole numbers from 1 through 8, and the submitted value is 9.

Inline message: “Enter a whole number from 1 to 8.” Check that both endpoints pass and that 0, 9 and fractional values trigger the same accurate guidance.

The workflow draws on the [W3C form notification tutorial](https://www.w3.org/WAI/tutorials/forms/notifications/).
