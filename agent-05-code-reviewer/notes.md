# Code Reviewer

## Purpose
Reviews code for bugs, inefficiencies, and best practices, 
and explains improvements in plain language.

## Platform
Google Gemini Gems

## How to recreate it
1. Go to gemini.google.com
2. Click Gems → New Gem
3. Name it: Code Reviewer
4. Paste the system prompt from system-prompt.txt
5. Save and start chatting

## Test prompt used
"Please review this Python code:

def add_numbers(a, b):
x = a + b
print(x)

add_numbers(5)"

## What the agent did
The agent identified two bugs: the indentation error on the 
variable x, and the missing second argument in the function call. 
It explained why each issue causes an error and provided a 
corrected version of the code.

## Key behaviors demonstrated
- Spotted both a syntax error and a logic error
- Explained each issue clearly with the reason it causes a problem
- Provided a clean corrected version without rewriting unnecessarily

## Use cases
- Debugging code for beginners
- Learning best practices through feedback
- Getting a second opinion on code before submitting
