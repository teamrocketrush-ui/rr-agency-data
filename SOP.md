# LinkedIn Report Manager — Standard Operating Procedure (SOP)
### TeamRocketRush | Version 1.0 | Last Updated: June 2026

---

## WHAT IS THIS SYSTEM?

This is an automated LinkedIn analytics reporting tool. You upload a client's LinkedIn Excel file, and the system automatically builds a live dashboard and publishes it online. The client gets a permanent link they can open anytime to see their report.

No coding. No design. No manual work. Just follow this SOP.

---

## BEFORE YOU START — ONE-TIME SETUP

1. Go to **claude.ai** and sign in with your work account
2. In the left sidebar, find the project called **"LinkedIn Report Manager"**
3. Click on it — this is your workspace. You will always work from here.
4. Bookmark this project link so you can find it quickly every time.

That's it. You're set up. Never start a conversation outside this project.

---

## THE THREE THINGS YOU CAN DO

| Action | When to use it |
|---|---|
| **Update a client** | Monthly — add a new month's report to an existing client |
| **New client** | When a brand new client joins the agency |
| **Re-upload / Fix** | When you uploaded the wrong file or wrong month and need to redo it |

---

## HOW TO START EVERY SESSION

**Always start by typing:** `Hi`

The system will automatically load the latest client list and show you:

```
👋 Welcome to the LinkedIn Report Manager!

Here are your active clients:
1. Nikhil Mishra — Apr 2026, May 2026 ✅
2. Anmol Sharma  — May 2026 ✅

What would you like to do?
→ Type a client name to update their report
→ Type 'New Client' to add someone new
→ Type 'Fix [client name]' to re-upload a report
```

---

## SCENARIO 1 — UPDATING AN EXISTING CLIENT (Monthly Report)

**Use this when:** It's a new month and you need to add that month's report.

### Step by Step:

**Step 1** — Download the client's LinkedIn Excel file
- Log into the client's LinkedIn account
- Go to Analytics → Export
- Download the Excel file for the correct date range
- Save it somewhere easy to find (Desktop works fine)

**Step 2** — Open the Claude Project and type `Hi`
- Wait for the client list to load

**Step 3** — Type the client's name
```
Example: Nikhil Mishra
```

**Step 4** — The system will ask what month. Type it clearly:
```
Example: June 2026
```

**Step 5** — The system will ask you to upload the file
- Click the **paperclip / attachment icon** in the chat
- Select the LinkedIn Excel file you downloaded
- Press Enter

**Step 6** — Review the confirmation summary
The system will show you:
```
✅ Ready to build. Here's what I found:
- Client: Nikhil Mishra
- Month: June 2026
- Total Impressions: 1,23,456
- Total Engagements: 892
- New Followers: 241
- Peak Day: June 14 with 45,230 impressions

Shall I build and deploy? (yes / no)
```

**CHECK THESE NUMBERS.** Do they look roughly right for this client?
- If yes → type `yes`
- If something looks wrong → type `no` and tell the system what's wrong

**Step 7** — Wait for confirmation (takes about 30-60 seconds)
```
✅ Done! Nikhil's June 2026 report is live.
🔗 https://teamrocketrush-ui.github.io/nikhil-mishra-report/
```

**Step 8** — Open the link and verify
- Open the link in your browser
- Check the month dropdown — June should be there
- Click through a few sections to make sure it looks right
- Send the link to the client or your manager

**Done!** ✅

---

## SCENARIO 2 — ADDING A NEW CLIENT

**Use this when:** A brand new client has been onboarded and needs their first dashboard.

### Step by Step:

**Step 1** — Download the client's LinkedIn Excel file (same as above)

**Step 2** — Open the Claude Project and type `Hi`

**Step 3** — Type: `New Client`

**Step 4** — The system will ask for the client's full name. Type it exactly:
```
Example: Rahul Verma
```

**Step 5** — The system will ask you to upload the file and tell it the month
- Upload the Excel file
- Type the month:
```
Example: June 2026
```

**Step 6** — Review and confirm (same as Scenario 1 Step 6)
- Type `yes` if everything looks correct

**Step 7** — Wait for confirmation
```
✅ Rahul Verma is now live!
🔗 https://teamrocketrush-ui.github.io/rahul-verma-report/

Share this link with your client — it will never change.
✅ Database updated.
```

**Step 8** — Save the link
- Copy the link
- Save it in the client tracking sheet
- Share with your manager and the client

**Done!** ✅

---

## SCENARIO 3 — RE-UPLOAD / FIX A REPORT

**Use this when:**
- You uploaded the wrong Excel file
- You selected the wrong month
- The numbers in the confirmation looked wrong and you said no
- The client pointed out an error in their report

### Step by Step:

**Step 1** — Open the Claude Project and type `Hi`

**Step 2** — Type: `Fix [client name]`
```
Example: Fix Nikhil Mishra
```

**Step 3** — The system will ask which month needs fixing:
```
Which month would you like to re-upload?
(Nikhil currently has: April 2026, May 2026)
```

Type the month:
```
Example: May 2026
```

**Step 4** — The system will say: `Please upload the correct file for May 2026.`
- Upload the correct Excel file

**Step 5** — Review the new confirmation summary
- Make sure the numbers now look correct
- Type `yes` to proceed

**Step 6** — The system will rebuild and redeploy that month
```
✅ Done! May 2026 has been updated on Nikhil's dashboard.
🔗 https://teamrocketrush-ui.github.io/nikhil-mishra-report/
✅ Database updated.
```

**Done!** ✅

---

## DOWNLOADING THE LINKEDIN EXCEL FILE — QUICK GUIDE

1. Log into the client's LinkedIn account
2. Click **Me** (top right) → **View Profile**
3. Click **Analytics** in the dashboard
4. Scroll down → click **Export**
5. Select date range:
   - For a monthly report: set exactly the first and last day of the month
   - Example for June: June 1, 2026 to June 30, 2026
6. Click **Export** — the file downloads automatically
7. The file name will look like: `AggregateAnalytics_ClientName_DateRange.xlsx`
8. Keep this file — do not rename it

---

## THINGS TO CHECK BEFORE CLICKING YES

When the system shows you the confirmation summary, always check:

✅ **Client name** — is it the right client?
✅ **Month** — is it the correct month?
✅ **Total Impressions** — does this number seem realistic for this client?
✅ **New Followers** — does this seem right?
✅ **Peak Day** — was there a viral post around that date?

If any of these look wrong → type `no` → tell the system what seems off → it will ask you to re-upload.

---

## COMMON MISTAKES AND HOW TO FIX THEM

| Mistake | What to do |
|---|---|
| Uploaded the wrong client's file | Type `no` at confirmation → re-upload the right file |
| Wrong date range in the Excel | Download the file again with correct dates → use Scenario 3 |
| Typed the wrong month | The system will catch it if dates don't match — just correct it |
| Report looks wrong after publishing | Use Scenario 3 — Fix — to re-upload |
| Client says numbers are wrong | Check the original LinkedIn export → use Scenario 3 to fix |
| System says client not found | Check spelling → try typing the name differently |

---

## WHAT NOT TO DO

❌ Do not upload the file without checking the confirmation summary
❌ Do not type `yes` if the numbers look obviously wrong
❌ Do not close the chat tab mid-task — wait for the "Done" confirmation
❌ Do not start a new conversation if the system is still working
❌ Do not share the Claude Project link with the client — it is internal only
❌ Do not share client data files outside the team

---

## IF SOMETHING GOES WRONG

If the system gives an error or stops responding:

1. Note what step you were on
2. Do NOT start over immediately — tell your manager first
3. Once confirmed, start a fresh conversation by typing `Hi`
4. Use Scenario 3 (Fix) to redo only what went wrong

---

## MONTHLY CHECKLIST

Use this checklist every month for each client:

```
Client: ___________________
Month: ____________________

[ ] Downloaded Excel from LinkedIn
[ ] Verified correct date range in file
[ ] Opened LinkedIn Report Manager project
[ ] Typed Hi — client list loaded correctly
[ ] Selected correct client name
[ ] Uploaded correct Excel file
[ ] Reviewed confirmation summary — numbers look right
[ ] Typed yes to confirm
[ ] Received Done confirmation
[ ] Opened live link and checked report
[ ] Verified new month appears in dropdown
[ ] Reported link to manager / client
```

---

## QUICK REFERENCE — COMMANDS

| What you want to do | What to type |
|---|---|
| Start session | `Hi` |
| Update existing client | Client's name (e.g. `Nikhil Mishra`) |
| Add new client | `New Client` |
| Fix a wrong report | `Fix Nikhil Mishra` |
| Cancel current action | `no` |
| Confirm and deploy | `yes` |

---

## CONTACTS & SUPPORT

If you are stuck or something is not working:
- Contact your manager immediately
- Do not attempt to fix GitHub or technical issues yourself
- The system is designed to be recoverable — nothing is permanent until you type `yes`

---

*SOP maintained by TeamRocketRush Management*
*System built on Claude (Anthropic) + GitHub Pages*
*For system changes, contact the project owner*
