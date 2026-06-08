# ClarityTool — Concept Demo

**Real-time manipulation detection. 90 documented techniques.**

> “Not *is this fake?* — but *how is this trying to influence me, and why does it work?*”

## What this is

A working concept demo for ClarityTool — a browser extension and mobile app that functions as a real-time manipulation awareness layer.

Paste any headline, email, political statement, or ad copy. The tool identifies which psychological techniques are being used, explains the mechanism in plain language, and assigns a manipulation score.

ClarityTool never judges whether content is true or false. It only names the technique. The user decides.

## How to deploy (GitHub Pages)

1. Fork or clone this repository
1. Go to **Settings → Pages**
1. Under *Source*, select **Deploy from a branch**
1. Select branch: `main`, folder: `/ (root)`
1. Click **Save**

Your demo will be live at:
`https://yourusername.github.io/claritytool/`

That’s it. No build step. No dependencies. Pure HTML.

## Technique database

90 documented manipulation techniques across 8 categories:

|Category                    |Techniques|
|----------------------------|----------|
|1. Emotional Triggers       |#1–#16    |
|2. Cognitive Biases         |#17–#30   |
|3. Authority & Trust Signals|#31–#41   |
|4. Social Mechanisms        |#42–#54   |
|5. Framing & Language       |#55–#69   |
|6. Information Manipulation |#70–#81   |
|7. Behavioral Triggers      |#82–#89   |
|8. Discourse Suppression    |#90       |

Academic basis: Bernays (1923), Cialdini, peer-reviewed research, PSYOP doctrine.

## Tech

- Single HTML file — zero dependencies, zero build tooling
- Uses Claude API (claude-sonnet-4) for real-time analysis
- API key handled server-side by Claude.ai infrastructure

## Contact

UNRLD. Studio · [joey@unrld.de](mailto:joey@unrld.de)

-----

*ClarityTool is a concept in development. June 2026.*