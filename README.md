# action-repo

This is a dummy repository created to trigger GitHub Webhook Events (Push, Pull Request, Merge) for the Developer Assignment.

## Usage

- Make changes to files and push to trigger `push` event
- Create a pull request to trigger `pull_request` event
- Merge a pull request to simulate a `merge` event

Webhook is sent to the companion `webhook-repo` Flask app which saves data to MongoDB and displays in real-time.
# Test webhook - pushed at 7:10 PM
