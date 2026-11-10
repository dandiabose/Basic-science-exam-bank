# Basic-science-exam-bank
Medical Basic Sciences Q-Bank Project | Developed a digital resource with 1,000+ practice questions to support undergraduate medical students in foundational biomedical sciences. Designed for active learning and structured exam prep, the project enhances self-assessment and curriculum mastery.

Single-file medical exam question banks that run entirely in the browser. Open an HTML file and start practising. There is no install, no server and no account. Optional Gemini AI features write answers and explanations for questions that have no stored key.

Built for medical students in Ethiopia preparing for qualifying and exit exams.

Features
Practice by chapter and topic. Pick any mix of chapters or topics, set the number of questions, and shuffle or keep the order.
Filters. All, MCQ only, missed, unseen, bookmarked, "check key" (answers flagged as doubtful), and repeated questions. A source filter shows which exam or file each question came from.
Difficulty focus. Practise only the hardest 10%, 20% or 50% of the questions in each selected topic. Difficulty comes from an AI rating (1 to 5) that is saved in your browser, plus your own miss rate.
AI answers (optional). For questions without a stored key, Gemini writes the answer and a short explanation the first time you open the question. Results are saved so each question is only graded once.
Several API keys. Add more than one Gemini key. Requests rotate across the keys, and a rate-limited key is skipped.
Progress tracking. Attempts, accuracy, bookmarks and your session are saved in your browser. A second store (IndexedDB) is used if normal storage is blocked.
Backup. Export your progress to a JSON file and import it into a newer version of the file. API keys are never included in an export.
Duplicates merged. Questions that appear in several exams or files are kept once, with all their sources listed.

Contributing

Corrections to answers, topics and explanations are welcome. Open an issue with the question text and the correction, or send a pull request that edits the question data.

Disclaimer

For education only. This is not medical advice and not an official exam resource. Questions were compiled from past exams, student notes and study materials. Make sure you have the right to share any question content before you publish it.

