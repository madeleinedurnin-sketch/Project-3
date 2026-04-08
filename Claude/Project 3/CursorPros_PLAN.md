# Project 3: Group Research Plan

**Course:** KIN 7518 Social Issues in Sport
**Group Name:** CursorPros

## 1. Research Questions & Significance

### RQ 1

**The Question:** 
How do audiences across different social media platforms (YouTube, X, and Instagram) negotiate and react to the blending of sports entertainment and political messaging in the context of Donald Trump's appearance on Bryson DeChambeau's "Break 50" series?

**The Context:**
This question addresses the phenomenon of political figures utilizing athlete-driven, non-traditional sports media to bypass traditional journalistic scrutiny and reach highly engaged demographics. By appearing on a casual, golf-focused YouTube series, it highlights the tension between sports as an "escape" and sports as a political platform.
*   **Current events:** This reflects a growing trend of political candidates leveraging alternative media, podcasts, and sports-adjacent YouTube circuits to soften their image, alongside the ongoing politicization of golf (e.g., LIV Golf's political ties).
*   **Relevant theoretical perspectives:** *Mediatization of Sports* (Sociology/Media Studies) and *Platform Affordances* (Communication). Mediatization perfectly frames how political actors use sports media logic to normalize their image. Platform affordance theory is necessary to justify why we are comparing three different datasets—the distinct architectures and cultural norms of YouTube (community-driven, longer engagement), X (high-velocity, inherently political), and Instagram (visual, brand-focused) inherently shape the polarization and nature of the discourse we will observe.

**Why It Matters:**
*   **Who cares:** Athlete-creators, sports marketers, political communication strategists, and sports sociologists.
*   **Why now:** We are amidst a massive shift where independent athlete-creators hold as much or more media power than traditional sports networks. Understanding how overtly political presence performs on these channels is critical for modern campaign strategies and athlete brand management.
*   **What's at stake:** For athletes (like DeChambeau), the stakes involve balancing tremendous viral viewership growth against potential brand polarization and sponsor backlash. For audiences, it demonstrates the ongoing collapse of sports as a politically neutral "safe space," illustrating how deeply political polarization permeates modern leisure and entertainment consumption.

## 2. Dataset Selection & Justification
**Dataset Choice:** B50/Trump Discourse

**Justification:** Due to the political and sports crossover nature of RQ1, the "Break 50" data specifically examines public response to Trump appearing with Bryson DeChambeau across multiple visual and text-based platforms. This allows for cross-platform comparison of political sports discourse.

**Key files you plan to use:**
*   `B50_INS_COMMENT.xlsx`
*   `B50_X_COMMENT.xlsx`
*   `B50_YT_COMMENT.xlsx`

## 3. Preliminary Variable Operationalization
| Construct | Operational Definition | Data Source / Indicator |
| :--- | :--- | :--- |
| **Political Alignment Discourse** | Comments explicitly expressing support or condemnation of Donald Trump or his policies. | Keywords (e.g., "MAGA", "vote", "election", "Trump2024", "dictator") in text columns across all platforms. |
| **Sports Escapism ("Keep Politics Out")** | Comments complaining about the presence of a political figure in a sports video or requesting focus on golf. | Phrases like "stick to golf," "unsubscribed," "keep politics out of sports," or "just want to watch golf." |
| **Platform-Specific Polarization** | The intensity and incivility of the political debate compared across platforms. | Swear word frequency, caps lock usage, and ratio of replies/likes on politically charged comments. |

## 4. Proposed Analyses
| Analysis Type | Description | RQ Addressed |
| :--- | :--- | :--- |
| **Thematic Keyword Analysis** | Count the frequency of political vs. golf-centric keywords to see which theme dominates the comment section on each platform. | RQ 1 |
| **Cross-Platform Sentiment Comparison** | Compare the aggregate sentiment (positive/negative/neutral) of the top 500 most-liked comments across X, YouTube, and Instagram. | RQ 1 |
| **Engagement Ratio Analysis** | Analyze if politically charged comments receive a higher ratio of replies-to-likes compared to golf-focused comments, indicating higher controversy. | RQ 1 |

## 5. Limitations & Potential Issues
1. **Bot & Troll Interference:** Political discourse on X and YouTube is heavily influenced by bot accounts and coordinated trolling, which may skew the perceived "audience" consensus.
2. **Context Collapse:** Sarcasm and irony are prevalent in internet comments but are notoriously difficult to accurately code or categorize, potentially leading to misinterpretation of sentiment.
3. **Selection Bias of the "Break 50" Audience:** Bryson's existing fanbase may already lean towards certain political demographics, meaning the reactions cannot be generalized to the entire golf or sports-viewing public.

## 6. Ethical Considerations
*   **Privacy:** The data is pulled from public comment sections on major social media platforms. However, to minimize risks, we will aggregate findings rather than singling out non-public individuals, and we will anonymize or paraphrase specific quotes from everyday users.
*   **Harm:** Analyzing highly polarized political discourse involves engaging with potentially toxic, racist, or inflammatory language. We must ensure our reporting and excerpts highlight the *structural discourse* without unnecessarily amplifying harmful rhetoric. 
*   **Bias:** As researchers, we must confront our own political biases or preconceived notions about either Trump or the LIV/PGA golf divide to ensure our coding is objective and reliable.

## 7. Group Role Assignments
| Role | Group Member | Primary Responsibilities |
| :--- | :--- | :--- |
| **Data Lead** | Hailee | Data cleaning (handling missing values in Excel sheets), standardizing columns across platforms, and keyword extraction. |
| **Methods Lead** | Madeleine | Designing the coding framework, managing the repository/versions, and verifying the logic of the cross-platform sentiment comparison. |
| **Theory Lead** | Kaylee | Rooting the findings in Platform Affordances theory, drawing connections to broader political trends, and drafting the final interpretations. |

## 8. Data Visualization Plan
**Primary Goal:** To illustrate whether the audience discourse was primarily focused on golf/entertainment or highjacked by political messaging, and how this varied by platform.

**Visualization Description:** A 100% stacked bar chart (three bars: YouTube, X, Instagram). Each bar will display the percentage breakdown of comments categorized as "Golf/Sports-Centric," "Politically Supportive," "Politically Critical," and "Neutral/Other."

**Design Rationale:** A 100% stacked bar chart is the most effective way to directly compare proportional breakdowns across three distinct platforms, immediately highlighting which platform fostered the most political vs. sports discourse.

**Verification Methods:**
*   Spot-checked calculations against source data.
*   Had groupmate review for accuracy.
*   Verified percentages add up to 100% for each platform.

**The Visualization:**
*[Visualization graphic to be generated/inserted here based on the dataset analysis]*

**Brief Interpretation:** *(Draft)* This visualization will demonstrate whether X's architecture fostered a significantly more politically polarized discourse compared to the longer-form, community-focused comments native to the YouTube audience.

## 9. AI-Assisted Work Documentation & Verification
**Tools Used:** Antigravity (Claude) via CLI to explore the datasets, construct the research questions, and formulate the methodological structure.

**Verification Methods:**
*   **Output Validation:** I reviewed the theoretical frameworks suggested by the AI (Mediatization and Platform Affordances) against course concepts to verify their academic appropriateness. 
*   **Dataset Verification:** I confirmed the AI's script properly loaded real row samples from the provided `.xlsx` data files before accepting the proposed variables.

**Learning Reflection:** Working with AI on constructing an academic plan taught me how to bridge raw datasets with high-level media theory. While the AI rapidly synthesized ideas, I had to actively evaluate whether the "Platform Affordances" theory truly fit our cross-platform data, teaching me to treat AI outputs as a foundational draft rather than a final submission.
