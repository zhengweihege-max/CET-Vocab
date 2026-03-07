# Active Mode Specification (CET-4 Vocab Internalization)

## 1. Trigger
User input: `[Article Text] + Active`

## 2. Vocabulary Selection Criteria (CRITICAL)
- **Target Count**: 8-10 words.
- **Difficulty Level**: CET-4 Standard/Advanced.
- **Exclusion**:
  - Exclude extremely simple words (e.g., *happy, problem, believe, make, see*).
  - Include words that are key to understanding but might be challenging for intermediate learners (e.g., *allegedly, violate, charge, capture, prohibit, intention, administration*).
- **Context**: Words must be relevant to the article's theme.

## 3. Exercise Structure (8 Sections - Full Suite)
### Phase 1: Input & Recognition (初阶)
1.  **The Glossary (音形义讲义)**
    - Word + Phonetic + POS.
    - **TTS Button**: `🔊` (Calls `speak('word')`).
    - **Original Sentence**: Extracted from text, target word **bolded**.
    - **Example Sentence**: New sentence (15-25 words), CET-4 style, with CN translation.
2.  **Meaning Matching (释义连线)**
    - Left: English Word.
    - Right: Chinese Definition.
    - Interaction: Click-to-match.
3.  **Contextual Gap-filling (语境还原填空)**
    - Original paragraph with blanks.
    - Hint: First letter + blanks.

### Phase 2: Intake & Manipulation (中阶)
4.  **Collocation Match (词块/搭配匹配)**
    - Focus: Verb+Obj, Adj+Noun, Prepositions.
    - Format: Left-Right matching.
5.  **Grammatical Transformation (语法填空/变形)**
    - 5 independent sentences.
    - Task: Fill in correct form (e.g., *violate* -> *violations*).
6.  **Auditory Recognition (听音辨位)**
    - Play audio -> Choose from 4 similar-sounding/looking options.

### Phase 3: Output & Application (高阶)
7.  **Mini-Cloze (微型完型填空)**
    - New short text (80 words) related to theme.
    - 7 choices for 5 blanks (Dropdown).
8.  **Partial Translation (局部重构中译英)**
    - English sentence with Chinese part to translate.
    - Must use target vocab.

## 4. HTML/Tech Specifications
- **Single File**: All CSS/JS embedded.
- **Student Registration**: Required at start.
- **TTS Engine**: Rate `0.8`, High-quality voice priority.
- **Validation**:
  - Auto-grading.
  - **Answer Key**: Hidden until submission.
  - **Report Card**: Name, Class, Score.

## 5. Visual Style
- **Theme**: Blue/Academic (`#2563eb`).
- **Layout**: Clean, card-based.
