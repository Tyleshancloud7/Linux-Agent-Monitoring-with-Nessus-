# Linux-Agent-Monitoring-with-Nessus-
🐞 Nessus Agent Madness: Linux Edition 🚀
“I put a bug in your Linux… now it finds all the bugs.” 🕷️💻
Turn your boring Linux VM into a vulnerability-hunting machine with Tenable Nessus Agent. Here’s how to do it like a pro (and have fun along the way):

Step 1: Create Your Playground
* Make an Agent Group in Tenable. Name it anything cool — just don’t use spaces.
* Create a Triggered Scan and select your new group.
* Pick a trigger filename (for example: dishsoap.lol) and brace yourself for magic.

Step 2: Prep Your Linux VM
* Log in with your new username and password.
* If your Mac complains about known hosts, delete the old entry — the VM doesn’t bite.
* Go to the Tenable Portal and start provisioning your Nessus Agent. Copy the command they give you, tweak it if you want, and run it on your VM.
* Wait for it to finish installing. Celebrate like you just hacked into the Matrix.

Step 3: Trigger the Scan
* Drop your trigger file into the Nessus Agent’s trigger folder.
* Watch it disappear like magic — that means your scan has started.
* If it’s being stubborn, restart the agent service and peek again.
* When the file vanishes, grab a coffee — your agent is officially hunting vulnerabilities.

Step 4: Watch the Action
* Check your Tenable Portal: your agent should show up as linked.
* Go to your triggered scan and watch the vulnerabilities populate.
* Monitor the VM if you want — it’s like watching a cat chase a laser pointer, but nerdier.

Step 5: Cleanup (Optional)
* Export scan results if needed.
* Delete the scan, the agent group, and unlink agents.
* Delete the Linux VM if you want a clean slate.

Troubleshooting Tips
* VM acting weird? Re-image it.
* Scan doesn’t show? Delete and recreate.
* Agent gone rogue? Hard delete it in Tenable.
* Still broken? Cry a little, then ask the community — we’ve all been there.

“The only bugs you want in your system are the ones Nessus finds.” 🐞💥

