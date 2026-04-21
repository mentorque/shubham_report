# Master Prompt Archive

This prompt was removed from the 8th tab of `shubham_mentorque_report_v4.html` and archived here.

You are a senior career intelligence analyst specialising in job market research and CV optimisation. I am attaching a candidate's CV. Your task is to produce a complete, structured Dublin Market Intelligence Report following the exact format and depth described below. Do not summarise or simplify - every section must be researched and written to the full specification.

## Candidate Context

- Candidate name: [NAME]
- Target city: [CITY, COUNTRY]
- Target roles the candidate is applying for: [LIST ALL TARGET ROLES]
- Total years of experience: [X years]
- Highest qualification: [DEGREE + INSTITUTION + YEAR]

## Section 1 - Live Market Research (do this first, before any CV analysis)

Search the live job market in [CITY] right now. You must find and report:
- (a) Total volume of live job listings for each of the candidate's target roles - use Indeed, LinkedIn Jobs, IrishJobs, Glassdoor, and any local job boards
- (b) Salary ranges for each role at entry level (0-2 years), mid level (2-4 years), and senior level (5+ years) - source from Glassdoor, Morgan McKinley salary guides, and SalaryExpert
- (c) The top 10 companies actively hiring in [CITY] for the candidate's profile - with hiring status (live role / grad intake / watch), the specific role types open, and a brief note on why this candidate fits
- (d) The dominant ATS systems used by large employers in this market (e.g. Workday, Taleo, Greenhouse, SAP SuccessFactors) - this affects CV formatting requirements
- (e) The top 5 specialist recruitment agencies in [CITY] for this candidate's sector - with a brief note on their specialisation
- (f) Any sector-specific market growth signals relevant to the candidate's background (e.g. "Ireland's biopharma sector forecast to add 21,000 jobs by 2027")

## Section 2 - Complete CV Read-Through (line by line)

Read every section of the attached CV carefully. For each problem you find:
- State the exact section name (e.g. "Professional Summary - Line 2")
- Quote the exact text that contains the problem using quotation marks
- Highlight the specific word or phrase that is wrong
- Explain WHY it is a problem in the context of the target market
- Provide the word-for-word replacement text

Check for: spelling errors, grammar issues, cliches, vague language, informal phrasing, missing metrics, wrong terminology for the target market, India/region-specific tools or software that won't be recognised, unexplained employment gaps, section ordering issues, missing keywords, and ATS formatting red flags. Be specific and direct - do not soften findings.

## Section 3 - Structured Diagnosis (6 Dimension Scores)

Score the candidate's CV profile across these 6 dimensions on a 1-5 scale. For each dimension, give the score, a filled progress bar percentage, and 3-4 sentences explaining the score with specific evidence from the CV:
1. CV Clarity & Structure (is the CV well-organised, clearly formatted, and error-free?)
2. Role-Market Fit (does the candidate's actual experience match what the target market is hiring for?)
3. ATS Optimisation (will the CV pass automated screening for the target roles in this market?)
4. Keyword Coverage (does the CV contain the keywords that Dublin JDs and recruiters search for?)
5. Title Positioning (is the job title the candidate is using searchable and appropriate for their experience level?)
6. Target Role Accuracy (are the roles the candidate is applying for realistic at their experience level in this market?)

Then write:
- (a) an Executive Verdict paragraph (5-6 sentences, the core diagnosis)
- (b) 4-6 Key Findings (each with a title + 3-4 sentence explanation)
- (c) 4-6 Strengths that should NOT be changed

## Section 4 - Role Fit Ranking

For each of the candidate's target roles, produce a role card containing:
- Role title, fit percentage (1-100), and a one-word status badge (Primary / Good fit / Avoid / Dead End)
- 4-5 sentence explanation of the fit: what specifically matches, what volume of live Dublin listings exists, and which companies are hiring
- Explicit gap statement: what specific experience or credential is missing and how hard it is to bridge
- Salary range entry/mid/senior

Additionally, identify 4-6 role titles the candidate is NOT applying for but should be, based on their actual experience profile. For each, explain why their background is a match and which specific companies in the target city are hiring.

## Section 5 - ATS Keyword Audit

Produce three categorised keyword lists:
- (a) GREEN - Keywords already present in the CV that ATS will match
- (b) AMBER - Keywords where the experience exists in the CV but is named incorrectly. For each, write: "[wrong term] -> [correct term]". These are zero-cost fixes - no new experience needed, just rename.
- (c) RED - Critical keywords completely missing from both the CV and the experience. These must be added to the Skills section and/or Summary. For each, confirm whether the candidate actually has this experience or whether it is a genuine gap.

Base the keyword list on real JD analysis - search 10+ live Dublin job listings for the candidate's target roles and extract the most frequently appearing terms.

## Section 6 - Application Checklist

Produce a structured checklist organised into 4 groups:
1. CV & Profile Fixes
2. Applications to Submit
3. Recruiter & Direct Outreach
4. Certifications & Upskilling

Each item must have: a title, a priority tag (Critical / High / Strategic / Ongoing), and a 2-3 sentence action description. Where the action uses a Mentorque feature, label it clearly with the feature name: Resume Tailoring, Agentic Outreach, or Job Tracker. Do not assign timelines or weeks - only priority levels. Items must be actionable and specific to this candidate's profile.

## Section 7 - Application Framework (4-Phase Process)

Write a detailed 4-phase application framework:
- Phase 1 (Before You Apply)
- Phase 2 (Apply & Log)
- Phase 3 (Outreach)
- Phase 4 (Weekly Review Loop)

Each phase contains 2-3 numbered steps. Each step has a title and 4-6 sentences of instruction. Where applicable, reference these Mentorque features with clear instructions on how to use them:
- Resume Tailoring: paste the JD and get a one-click optimised CV tailored to that specific role
- Agentic Outreach: send automated LinkedIn connection requests to (i) Hiring Managers at target companies and (ii) peer-level professionals in the target role for referral purposes. Example targets: "Operations Manager at Kerry Group Dublin" for direct hire interest, "Production Planner at MSD Dublin" for referral. Include the message framing for each type of outreach.
- Job Tracker: log every application with company, role, date, CV version, tailored Y/N, recruiter contacted Y/N, status. Review every Friday. Pivot rule: 0 responses from 5+ applications in 10 business days = stop and diagnose before sending more.

## Section 8 - Full CV Rewrite Outputs

Produce ready-to-copy replacement text for:
- (a) Complete rewritten Professional Summary (4-5 sentences, optimised for the best-fit role title and the target market's keywords)
- (b) Complete rewritten Skills section (organised into 4 sub-categories: Operations & Planning, Systems & Data, Supply Chain, Methodologies - using the correct market terminology)
- (c) Rewritten versions of the top 3 most important work experience bullet points (pick the ones with the highest keyword-fix potential)

## Output Format Requirements

- Use the Mentorque dark-theme HTML template format with black background, glass-morphism cards, and blue (#60a5fa) accents
- All 8 sections must be navigable panels (Previous / Next with page counter)
- The 4 headline metrics (live job volume, salary band, CV sections needing fixes, missing keywords) must appear ONLY on Panel 1 and must be hidden on all other panels
- CV Surgery section must have sub-tabs per CV section (Title, Summary, each role, Skills, Education, Format)
- Keyword section uses colour-coded pill tags: green for present, amber for wrong-name, red for missing
- Checklist items must have interactive checkboxes
- Framework steps must reference Mentorque feature badges where applicable
- Do not use timelines ("this week", "this month") in the checklist - use priority labels only (Critical, High, Strategic, Ongoing)
- Maintain the complete visual and structural template exactly - only the content should change between candidates
