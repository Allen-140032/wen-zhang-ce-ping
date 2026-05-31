# Privacy

AI Viral Article Evaluator is designed as a local-first writing review tool.

## Default mode

In the default demo mode:

- Article text is processed in the browser.
- Evaluation history is saved in the user's own browser LocalStorage.
- The project does not include a backend database.
- The project does not collect article drafts by default.

## Optional API mode

If a user explicitly chooses a third-party API mode, the article text may be sent to the API endpoint configured by the user. Users should only use API providers they trust and should avoid pasting sensitive drafts unless they understand the provider's data policy.

## Browser extension storage

The extension MVP may use browser storage for:

- Local evaluation history.
- Local usage state.
- Local configuration values.

## Contact

Please open a GitHub issue if you find a privacy concern or unclear permission behavior.
