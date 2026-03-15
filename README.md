# Natural Language OS Interface

Python app that translates plain English commands into OS-level shell commands using GPT-4 API.

## What it does
- Type natural language (e.g. "show running processes") → executes the correct terminal command
- Sandboxed execution environment prevents unauthorized command execution
- Supports multi-turn conversations and complex error-handling protocols
- Modular structure with separate src, tests, and ui components

## Files
| File | Description |
|------|-------------|
| `src.zip` | Full source code (main app, security layer, command executor) |
| `requirements.txt` | Python dependencies |

## Setup
1. Clone the repository
2. Install dependencies:
