# Data Feedback Dataset

The repository stores the feedback examples as the text-based file `data_feedback.csv` to avoid binary artifacts in version control. Each row mirrors the original Excel table and contains:

- `S#`: Row identifier
- `teacher/course`: Whether the comment refers to a teacher or course
- `comments`: Free-text feedback
- `sentiment`: Overall sentiment label
- `aspect`: Aspect category (e.g., teaching skills, behaviour, relevancy)
- `length`: Character length of the original comment

If you need an Excel version (e.g., to follow the notebook), run the provided notebook or a short pandas snippet to export the CSV to `data/data_feedback.xlsx` before loading with `pd.read_excel`.
