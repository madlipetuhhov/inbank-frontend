# Task

Validate TICKET-101 and write a conclusion for it as .md in the project directory. Make sure
that the code works according to the requirements. Make sure to highlight what the intern
did well as places for improvement. Tip: The more SOLID the better.
Highlight the most important shortcoming of TICKET-101 with explanation. Fix it!

# Review

NB! Feedback about back-end is in the .md file in the back-end in a file "TICKET-101.md".

Decision engine returns decision, both negative or positive, and the amount. However, the negative message is returned
with the amount and period. This makes the answer for customer difficult to understand. I would also change the negative
response message "No valid loan found!" more specific.

Loan period leverage minimum limit is 12 months, not 6 months. Should be fixed and controlled if the data is correct.

The design of the page is clean and simple, and the possibility of entering unsuitable data is minimized.

# Fixes

Fixed logic of returning negative decision and loan amount. With the error message, the amount and period are not displayed.

Fixed loan period leverage minimum limit to 6 months. The correct limits are used in the code.