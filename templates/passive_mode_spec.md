# Passive Mode Specification (CET-4 Vocab Internalization)

## 1. Trigger
User input: `[Article Text] + Passive`

## 2. Vocabulary Selection Criteria (CRITICAL)
- **Target Count**: 10-12 words.
- **Difficulty Level**: CET-4 Advanced / CET-6 Basic.
- **Exclusion**:
  - Exclude simple/high-school level words (e.g., *happy, benefit, blame, contribute, satisfaction, problem, believe*).
  - Exclude overly obscure words unless critical to the article.
- **Selection Priority**:
  - Academic/Formal verbs and nouns (e.g., *determination, discipline, entrepreneur, ethic*).
  - Adverbs ending in -ly (e.g., *automatically, permanently, allegedly*).
  - Strong adjectives (e.g., *incredible, critical, passionate*).

## 3. Exercise Structure (5 Sections Only)
### Phase 1: Input & Recognition (初阶)
1.  **The Glossary (音形义讲义)**
    - Word + Phonetic + POS.
    - **TTS Button**: `🔊` (Calls `speak('word')`).
    - **Original Sentence**: Extracted from text, target word **bolded**.
    - **Example Sentence**: New sentence (15-25 words), CET-4 style, with CN translation.
2.  **Meaning Matching (释义连线)**
    - Left: English Word.
    - Right: Chinese Definition (Simple & Direct).
    - Interaction: Click-to-match, auto-check color (Green/Red).
3.  **Contextual Gap-filling (语境还原填空)**
    - Original paragraph with blanks.
    - Hint: First letter + blanks (e.g., `d__________`).
    - Input: Text box.

### Phase 2: Intake & Manipulation (中阶)
4.  **Collocation Match (词块/搭配匹配)**
    - Focus: Verb + Object / Adjective + Noun / Prepositional phrases.
    - **Check**: Ensure collocations are idiomatic (e.g., *stick to a habit*, NOT *stick to permanently*).
5.  **Grammatical Transformation (语法填空/变形)**
    - 5 independent sentences.
    - Task: Fill in the correct form of the word given in brackets.
    - Focus: Word formation (noun -> adj, verb -> noun, etc.).

*Note: Auditory, Mini-Cloze, and Translation sections are REMOVED in Passive Mode.*

## 4. HTML/Tech Specifications
- **Single File**: All CSS/JS embedded.
- **Student Registration**: Modal at start (Name, Class, ID) -> Required before viewing content.
- **TTS Engine**:
  - Rate: `0.8` (Slower).
  - Voice Priority: Google US English > Microsoft Zira > Samantha > Daniel.
- **Validation**:
  - "Submit & Check" button at bottom.
  - Auto-grading (Score calculation).
  - **Answer Key**: Hidden by default, reveals ONLY after submission.
  - **Report Card**: Displays Student Info + Score + Percentage.

## 5. Visual Style
- **Theme**: Clean, Academic.
- **Colors**:
  - Primary: Sky Blue (`#0ea5e9`) or similar professional color.
  - Feedback: Green (`#22c55e`) for correct, Red (`#ef4444`) for wrong.
