# Decision Points

## 1. Deterministic risk detection
We chose explicit rule-based detection for Sensational, Shouting, and Unsourced signals. The challenge specifies exact trigger phrases and an uppercase threshold, so deterministic behavior is transparent and easy to test.

## 2. Human review status
We keep automatic risk signals separate from the reviewer verdict. This prevents the presentation style of a post from being treated as evidence that a claim is true or false.

## 3. Static browser-only access
We removed the backend and authentication so the complete MVP can run directly from GitHub Pages. Claims and reviews are persisted in localStorage on the current browser.
