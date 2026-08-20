# AHP-Decision-Teamworking
This is a AHP decision tool to make a decision as a team

You as a coordinater
-  Open the file, pick "I'm running the study," define the goal, criteria, alternatives.
-  Get a setup code — send this same file + that code to each teammate.
-  Optionally score it yourself too, in the same session.
-  As results come back, paste each person's result code into "Import results" (one at a time, or several lines at once) — it validates that their criteria/alternatives actually match your study before adding them.
-  Once you've collected what you need, hit Compute group result for the aggregated ranking, criteria weights, and a per-person "top pick" breakdown so you can see where the team agrees or splits.

Teammates as a participant
-  Open the same file, pick "I was sent a study to score," paste your setup code, enter their name
-  Score the criteria and alternatives on their own — goal/criteria/alternatives are locked in from your code, so nobody can accidentally rename or reorder things.
-  Get an export code at the end — that's the whole thing they send back to you.

Note that: 
-  It's a single html file work for both you just need to share codes within the team.
-  Save/resume: since this is a static file with no backend, your coordinator progress lives only in that browser tab. There's a " save progress" button that downloads a small session file — use it before closing the tab if results are still trickling in, and reload it later via "Resume a saved session" on the start screen
-  Mismatch protection: if someone's result code doesn't match your current criteria/alternatives (e.g., you edited the study after sending it out), the import step flags it instead of silently corrupting the aggregate
