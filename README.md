# ECA AI Foundations Deck

Presentation deck for Elite Career Academy — AI Foundations session.

## Working with this deck

The main file is `ECA_AI_Foundations.html` — self-contained HTML with all images embedded as base64.

## Git workflow

- Every significant change gets its own commit with a descriptive message
- To revert to a previous state: `git log --oneline` to find the commit, then `git checkout <commit> -- ECA_AI_Foundations.html`
- To see history: `git log --oneline --all`

## Opening the deck

Open `ECA_AI_Foundations.html` in a browser. Or run a local server:

```
python3 -m http.server 8765
# then visit http://localhost:8765/ECA_AI_Foundations.html
```
