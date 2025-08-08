# Troubleshooting — Baby Steps (8-step, fully explained)

Follow these steps exactly. For each sub-step you'll see: *Action*, *Why*, *What to look for*.

## Step 1 — Identify the problem
- **Action:** Ask the user to describe the symptom. Example: "Can you open https://www.google.com in your browser?"  
  **Click:** Open browser > address bar > type url > Enter.  
- **Why:** Verifies whether basic internet is working before troubleshooting more complex services.  
- **Look for:** Browser error (DNS error, page not found, timeout).

## Step 2 — Establish a theory of probable cause
- **Action:** Read error messages exactly. Copy/paste them into the ticket.  
- **Why:** Exact error text points to the subsystem (auth, server, DNS, driver).  
- **Look for:** Keywords like "authentication", "timeout", "unreachable", "error code 0x...".

## Step 3 — Test the theory
- **Action:** Try quick reversible checks. Example: Ping the server (Start > type cmd > Enter > type `ping <address>` > Enter).  
- **Why:** Fast checks confirm network-level reachability before changing configs.  
- **Look for:** Replies vs. request timed out.

## Step 4 — Plan the action
- **Action:** Decide safe steps (reinstall profile, reset service, escalate). Note them in the ticket before applying.  
- **Why:** Planning reduces risk of making the problem worse.
- **Look for:** Consensus from logs and tests.

## Step 5 — Implement the solution
- **Action:** Carry out one change at a time. Document each command or click.  
- **Why:** Makes rollback possible and keeps the ticket traceable.
- **Look for:** Any new error messages or system behavior.

## Step 6 — Verify full functionality
- **Action:** Test the user's original use-case (open app, access network share).  
- **Why:** Confirms the repair actually solves the user's need.
- **Look for:** Successful access and no new issues.

## Step 7 — Document findings and outcome
- **Action:** Write cause, steps taken, and final status in the ticket.
- **Why:** Saves time for future incidents.

## Step 8 — Prevent recurrence
- **Action:** Suggest user training, patching, or policy change. Attach short how-to for the user.
- **Why:** Reduces repeat tickets.
