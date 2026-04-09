# TrumpProject 3: Group Research Plan

**Course:** KIN 7518 Social Issues in Sport
**Due:** Friday, April 10, 2026 by 11:59 PM
**Submission:** Email to [yqian@lsu.edu](mailto:yqian@lsu.edu) — One member submits, **CC all group members**
**Format:** Markdown (.md) file
**File Naming:** `CursorPros_PLAN.md`

---

## 1. Research Questions & Significance

For each research question, address all three components below. The goal is to show the logical connection between the phenomenon you're investigating, the question you're asking, and why it matters.

### RQ 1

**The Question:**
How do audiences across different social media platforms (YouTube, X, and Instagram) negotiate and react to the blending of sports entertainment and political messaging in the context of Donald Trump's appearance on Bryson DeChambeau's "Break 50" series?

**The Context:**What phenomenon, debate, or gap does this question address? Connect to:

- Current events, public discourse, or real-world observations
- Relevant theoretical perspectives from *any* discipline (e.g., sociology, communication, psychology, marketing, cultural studies, media studies, gender studies, etc.)—**justify why your chosen framework is appropriate**

**Why It Matters:**
Who cares about this question? Why now? What's at stake for stakeholders (e.g., athletes, fans, media, organizations, policymakers, researchers)?

In the United States, the country is becoming increasingly partisian in its' political views. Politics are being treated like something we should not talk about as people have become more violent or outspoken in how they display their political beliefs. With the continued development of social media and technology, politicians are able to be more visibile and integrated into media we create. Poeple often debate if sport should be mutually exclusive from politics or if there is a way for them to have a positive relationship. It is important to look at the viability of integrating politics into sport and whether that is something that we can keep moving forward with to a certain extent or if the audience does not agree with putting them together.This question helps us take a closer look into this as people are extremely outspoken on both sides when discussing Donald Trump as a politician so it can give us some authentic insight into how we can either continue to develop this relationship and potentially profit or how it may lead to stunted growth for organizations.

---

## 2. Dataset Selection & Justification

Identify which dataset you are using and explain why.

**Dataset Choice: B50/Trump Discourse**

These three data sets are the perfect fit for our research question, as they directly align with the core components of our study. As they all are related to Bryson DeChambeau’s “Break 50” series and Donald Trump’s guest appearance solely, we have eliminated the noise surrounding DeChambeau or Trump’s general social media presence. By using data from three platforms, Instagram, X, and YouTube, we have diversified the range of comments that can be found. This is due to the true nature of the platforms and how the culture behind who uses them interacts with the coverage of “Break 50." In short, these datasets provide both the raw text needed to see how people are reacting to the blending of sports and politics, as well as the structural metrics needed to see where and how strongly those reactions are resonating across three fundamentally different social ecosystems.


**Key files you plan to use:**

- B50_INS_COMMENT.xlsx
- B50_X_COMMENT.xlsx
- B50_YT_COMMENT.xlsx

---

## 3. Preliminary Variable Operationalization

For your main constructs, describe how you will measure or identify them in the data.


| Construct                     | Operational Definition                                            | Data Source / Indicator                         |
| ----------------------------- | ----------------------------------------------------------------- | ----------------------------------------------- |
| Platform-Specific political stance expression  | Direct and explicit political positioning in the comments | Text coding of text in [B50_INS_COMMENT.xlsx], contents in [B50_X_COMMENT.xlsx], and text in [B50_YT_COMMENT.xlsx]; keyword dictionaries (e.g., “MAGA,” “rapist,” “president,” “former president,” party labels) plus manual validation sample. |
| Sports entertainment vs. political framing | Primary thematic frame used by commenters when interpreting the content | Content coding of same text fields using frame categories: sports/performance (e.g., “break 47,” gameplay skill), politics/ideology (candidate evaluations, ideology), blended (sports and political references in one comment). Optional support fields: hashtag in [B50_X_COMMENT.xlsx], source in [B50_YT_COMMENT.xlsx] |
| Engagement intensity of political sport reactions | Magnitude of audience reaction to comments that blend sports and politics compared with comments that do not blend | Engagement metrics linked to coded comments: likes and comment_re in [B50_INS_COMMENT.xlsx]; likes, reply counts, retweets count, reference count, Comment views in [B50_X_COMMENT.xlsx]; likes and comment_re in [B50_YT_COMMENT.xlsx] Compute platform-normalized averages/medians by frame and stance category. |


---

## 4. Proposed Analyses

Outline the analytical approaches you plan to use. For each, explain how it addresses your RQ.


| Analysis Type                      | Description                                             | RQ Addressed |
| ---------------------------------- | ------------------------------------------------------- | ------------ |
| Framing pattern comparison analysis | Compare prevalence of sports/performance, politics/ideology, and blended frames across YouTube, X, and Instagram | [RQ 1] |
| Stance-by-frame association analysis | Test whether political stance is associated with framing choice (e.g., whether pro/anti comments are more likely to be blended vs single-frame) within and across platforms. | [RQ 1] |
| Engagement differential analysis | Compare normalized engagement (likes/replies/retweets/views where available) between blended and non-blended comments, and by stance category | [RQ1] |


---

## 5. Limitations & Potential Issues

Identify at least 2-3 limitations or challenges with your approach. Be honest—acknowledging limits is a strength, not a weakness.

1. A significant limitation when analyzing user-generated content, especially at the intersection of sports and politics, is the difficulty of deciphering user intent. Comment sections are deeply embedded in internet culture and niche inside jokes. Whether you are employing automated natural language processing (NLP) for sentiment analysis or conducting manual human coding, it is notoriously difficult to accurately classify comments that use sports slang to indirectly make a political point, or vice versa. This inherent ambiguity can lead to miscategorization of the data, potentially skewing your findings regarding how boundaries are supposedly being "negotiated."

2. While cross-platform analysis is a strength of the study, it also presents a major structural challenge. You are not comparing "apples to apples." X fosters argumentative, text-heavy, real-time political discourse; Instagram is visual-first, resulting in reactions that often focus more on aesthetics or short-form emojis; and YouTube’s structure encourages longer-form, detailed essay-style replies. Developing a unified, standardized coding framework to accurately measure or compare "negotiation" across these three totally different social architectures is incredibly complex. A metric indicating deep engagement on X might mean something entirely different on Instagram, risking a misinterpretation of comparative behavior.

3. This methodology relies on datasets that capture a static snapshot of comments, representing the audience's immediate reactions at the time the data was scraped. However, online discourse, especially surrounding a polarizing political figure, is highly fluid. The way audiences negotiate the blending of sports and politics in this video might shift as the real-world political news cycle progresses or as the video gets shared in new contexts in the future. By relying on a fixed, historical dataset, the approach cannot capture how public perception evolves over time, restricting your findings to an immediate reactionary window rather than a long-term understanding of audience reception.

---

## 6. Ethical Considerations

Address the following:

- **Privacy:** Are you analyzing public or private data? Any risks of identifying individuals?
- **Harm:** Could your analysis reinforce stereotypes or cause harm to groups discussed?
- **Bias:** What biases might exist in your data or your interpretation?

**Privacy:**
In terms of privacy, this study relies solely on public data, specifically user-generated comments from publicly accessible posts on Instagram, X, and YouTube. However, these datasets contain identifiable metadata. To mitigate the risk of identifying specific individuals, the data will be treated confidentially during analysis. This means removing all usernames and personally identifiable markers.

**Harm:**
In terms of the potential for harm, the intersection of politics and sports, especially involving a polarizing figure like Donald Trump, naturally elicits heated, partisan, and sometimes toxic discourse. There is a risk that analyzing and presenting these comments could inadvertently amplify inflammatory political rhetoric or partisan vitriol present in the data. Generalizing the findings could reinforce stereotypes, such as making assumptions about the political ideologies of all golf enthusiasts or characterizing users of specific platforms grandiosely. To prevent this, the research must maintain strict academic objectivity, focusing on how audiences negotiate meaning and boundaries, rather than validating, judging, or giving an unfiltered platform to extreme sentiments.

**Bias:**
In terms of biases, there is a change for it to exist within both the data itself and its interpretation. Data-wise, the datasets only capture the sentiments of a highly engaged minority who felt strongly enough to leave a comment, leaving the reactions of the "silent majority" of viewers completely unknown. Additionally, the baseline audience skews towards the specific demographics of golf fans and Bryson DeChambeau subscribers, meaning the reactions are not representative of the general public. Furthermore, platform algorithms heavily bias what comments are seen or engaged with, often rewarding the most controversial or polarizing takes. Interpreting this data also carries the risk of researcher bias; because political comments are often subjective, sarcastic, or culturally nuanced, we must be careful not to project our own political leanings or assumptions onto the data during coding and thematic analysis.

---

## 7. Group Role Assignments

Specify who is responsible for what. Titles are flexible, but responsibilities must be clear.


| Role         | Group Member | Primary Responsibilities                                      |
| ------------ | ------------ | ------------------------------------------------------------- |
| Data Lead    | Hailee       | [e.g., Data cleaning, preprocessing, file management]         |
| Methods Lead | Madeleine       | [e.g., Analysis design, tool implementation, documentation]   |
| Theory Lead  | Kaylee       | [e.g., Literature integration, RQ refinement, interpretation] |
|              |              |                                                               |


---

## 8. Data Visualization Plan

Create at least ONE data visualization that addresses your research question(s). This is a required deliverable due with your project plan.

**Primary Goal:**
What story does your visualization tell? What specific question does it answer?

[Your response here]

**Visualization Description:**
Describe what type of chart/graph you're creating and what it will show. (e.g., "Bar chart comparing frequency of X vs. Y," "Line graph showing change over time," "Word cloud of most common themes")

[Your response here]

**Design Rationale:**
Why did you choose this visualization type? How does it clarify your argument or make your data more understandable?

[Your response here]

**Verification Methods:**How will you ensure your visualization accurately represents your data?

- Spot-checked calculations against source data
- Had groupmate review for accuracy
- Verified percentages/totals add up correctly
- Other: [specify]

**The Visualization:**
Embed your visualization here (as an image) or provide a link to the file.

[Insert visualization or link]

**Brief Interpretation (2-3 sentences):**
What does this visualization show? What pattern or insight does it reveal?

[Your response here]

---

## 9. AI-Assisted Work Documentation & Verification

If you used AI tools (Antigravity, Cursor, ChatGPT, etc.) for any part of this plan, document your process and verification methods.

**Tools Used:**
Which AI tools/IDEs did you use, and for what purpose?

We utilized Cursor and GitHub for Project 3. We used these to help develop and sort through our data and to store all of our work on the GitHub Repo.

**Verification Methods:**How did you verify AI outputs were accurate and appropriate?

- **Code Explanation:**
  - I asked AI to explain what each line/section of code does
  - I reviewed explanations and understand the logic
  - I asked AI to download code and save for review if needed.
- **Output Validation:**
  - I verified outputs make logical sense given my data
  - I compared AI results with what I know about my dataset
- **Iterative Refinement:**
  - Number of prompt iterations before getting usable output: ___
  - Key refinements made: [describe]

**Learning Reflection:**
What did you learn from working with AI on this project? What did examining the AI-generated code/outputs teach you?

[Your response here]

---

## Submission Checklist

Before submitting, confirm:

- All sections completed
- RQs are specific, contextualized, and significance is justified
- Dataset choice is confirmed
- At least one construct is operationalized
- Limitations and ethics are addressed honestly
- All group members are assigned roles
- Data visualization is included (Section 8)
- Visualization includes verification methods
- If AI tools were used, Section 9 is completed with verification documentation

---

**Submission Reminder:**

- **File name:** `GROUPNAME_PLAN.md` (e.g., `GeauxTigers_PLAN.md`)
- **Visualization file name:** `GROUPNAME_VISUAL.[extension]` (e.g., `GeauxTigers_VISUAL.pdf`)
- **Email to:** [yqian@lsu.edu](mailto:yqian@lsu.edu)
- **CC:** All group members
- **Deadline:** Friday, April 10th , 2026 by 11:59 PM

