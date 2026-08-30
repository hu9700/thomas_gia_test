# GIA Mock Test

A static, front-end-only mock of two tasks from the Thomas International GIA (General Intelligence Assessment) series. No server, no build tools, no dependencies — just open the files in a browser.

## Tasks

| File | Task | Time limit |
|------|------|------------|
| `index.html` | Menu / landing page | — |
| `task2.html` | Task 2: Perceptual Speed | 4 minutes |
| `task3.html` | Task 3: Number Speed & Accuracy | 3 minutes |

### Task 2: Perceptual Speed

Four vertical pairs of letters are shown. Count how many pairs contain the same letter (case-insensitive — `F` and `f` count as the same). Answer by clicking a box numbered **0–4**.

- Each question has a random orientation: the top row is either all uppercase (bottom row lowercase) or all lowercase (bottom row uppercase).
- Questions are generated on the fly; answer as many as possible before the timer runs out.

### Task 3: Number Speed & Accuracy

Three numbers are shown. Find the highest and the lowest, then determine which one is numerically further away from the remaining (middle) number. Click that number.

- The two distances (`diff1` and `diff2`) are both at least 5 and differ by at most 2, so the correct answer is never a tie.

## Results

After the timer ends, each task shows:

- **Correct %** — percentage of correct answers
- **Avg time / question** — mean response time
- **Answered** — correct / total answered
- **Score** — points earned (see scoring below)
- A per-question breakdown table (time and correct/wrong)

### Scoring

- Each correct answer: **+1 point**
- Task 2 — each wrong answer: **−0.25 points**
- Task 3 — each wrong answer: **−0.5 points**

## How to run

Open any file directly in a web browser (e.g. Firefox):

```sh
firefox index.html
```

No server or installation is required.

## Disclaimer

This is an unofficial mock for practice purposes only. It is not affiliated with or endorsed by Thomas International.
