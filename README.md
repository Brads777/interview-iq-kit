# Interview-IQ Project Kit

**MGT4850 Business Strategy, Northeastern University. G. Bradley Scheller**

Interview-IQ helps you run AI-executive interviews for a strategy case, keep the evidence, and turn it into a memo template and draft exhibits. This kit runs inside a **Claude Project**, so **there is nothing to install**. You don't need code execution or Skills, and it works with your Northeastern Claude account.

**The AutoVision Robotaxi case is already built in:** the assignment, the case background, the five executives, a full interview plan (28 planned questions with 66 follow-up probes, tagged to memo questions Q1–Q5), the coverage map and the memo template. You don't paste or upload any case material yourself.

> Looking for the Claude Skill version for personal accounts that allow Skills? It lives at [github.com/Brads777/interview-iq](https://github.com/Brads777/interview-iq).

## 1. Download

Go to the **[latest release](https://github.com/Brads777/interview-iq-kit/releases/latest)**, and under **Assets** download **`interview-iq-project-kit.zip`**. Unzip it. Inside are two files you'll use, plus a README:

| File | Where it goes |
|---|---|
| `Interview-IQ_Project_Instructions.txt` | Pasted into the Project's **Instructions** |
| `Interview-IQ_Robotaxi_Knowledge.md` | Uploaded to the Project's **Knowledge** |
| `README_Start_Here.txt` | These steps, in plain text |

## 2. Set up the Project (about 5 minutes, once)

1. In Claude, open **[Projects](https://claude.ai/projects)** and click **New project**. Name it **Interview-IQ Robotaxi**.
2. In the Project, click **Instructions** (it may say *Set project instructions*). Open `Interview-IQ_Project_Instructions.txt`, copy **all** of it, paste it in, and save.
3. In the Project's **Knowledge** (or **Files**) area, click **+** and upload `Interview-IQ_Robotaxi_Knowledge.md`.
4. Open a **new chat inside the Project** and type: `Run Interview-IQ`

Claude offers three choices:

- **A.** Run my Robotaxi interviews
- **B.** Resume from my saved Interview-IQ Log
- **C.** Build my memo template and draft exhibits

If it doesn't, check that the instructions were pasted into the Project's *Instructions* (not into a chat) and saved.

## 3. What happens

1. **Review the case.** A short fact sheet: the board's decision, Q1–Q5, the five executives and their stances, and the known gaps.
2. **Confirm the plan.** You see the pre-built interview order and the coverage map. Keep the plan, or reorder people and rewrite questions in your own words.
3. **The Interview-IQ Dashboard.** If your Claude can make artifacts, a dashboard opens in its own panel beside the chat. It shows your progress, the current question with a **Copy** button, the coverage map and the evidence so far. If artifacts aren't available, everything appears in the chat.
4. **Interview.** Open the case app in a second tab. Interview-IQ gives you one question at a time; you ask it in the case app and paste the executive's answer back into the chat. It suggests a follow-up when an answer leaves a gap (at most eight per planned question).
5. **Wrap up.** Choose **C** for a memo template in the course format and draft exhibits built only from your interviews, with every source cited and every gap flagged. Paste them into Word.

Interview-IQ **does not write your memo**. The Impact Summaries, the analysis and the recommendation are yours.

## Save your progress

At each checkpoint, Interview-IQ prints your **Interview-IQ Log** in one block. Copy it into a text file named `Interview-IQ Log.txt` and add it to the Project's Knowledge, replacing the older copy. If a chat gets too long, open a new chat in the same Project, type `Run Interview-IQ`, and choose **B**. You'll pick up where you stopped, and the dashboard is rebuilt.

## Repository contents

```
kit/    the kit files (the same files as the release zip)
dist/   interview-iq-project-kit.zip, attached to each release
```

## Need help?

Post in the course's Canvas discussion forum, or bring your question to the Zoom Sync.

---
© 2026 G. Bradley Scheller
