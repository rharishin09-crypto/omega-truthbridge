# OMEGA TruthBridge — Two Agents, One Truth

OMEGA TruthBridge is a prototype project that explores how two agents with different claims can compare their supporting evidence and work toward one clear, transparent conclusion.

## Problem

Different AI agents can provide conflicting answers to the same question. It can be difficult for users to understand why they disagree or whether the available evidence is enough to establish an answer.

## Proposed Solution

TruthBridge provides a simple interface where users can enter a question, each agent's claim, and the evidence supporting each claim. The prototype then displays a result based on the information entered and indicates when the evidence is incomplete or conflicting.

## Project Key Terms

- **OMEGA:** The framework targeted for integration in this hackathon project. Integration is planned and is not yet implemented in the current prototype.
- **Two Agents, One Truth:** The project concept of comparing two agents' answers to the same question and working toward one clear conclusion.
- **Agent A and Agent B:** The two perspectives represented in the current prototype by user-entered claims and evidence.
- **Claim:** A statement or answer proposed in response to the question.
- **Supporting Evidence:** Information provided to support a claim. In the current prototype, evidence is entered by the user and is not independently verified.
- **Evidence Comparison:** Reviewing the evidence associated with each claim to identify agreement, gaps, or conflicts.
- **Conflict Detection:** Recognizing when the two claims or their supporting evidence differ.
- **Consensus / Unified Conclusion:** A shared conclusion when the available information supports one. If the evidence is insufficient or conflicting, the result should communicate that uncertainty instead of guessing.
- **Transparent Reasoning:** Explaining how the entered claims and evidence relate to the displayed result.
- **Uncertainty Handling:** Clearly identifying missing, incomplete, or conflicting evidence rather than presenting an unverified answer as fact.
- **Human Review:** Checking the sources and evidence before relying on a conclusion for an important decision.
- **Python and Flask:** The programming language and web framework used to build the current web prototype.
- **MeTTa / BASIX:** Terms associated with the wider hackathon ecosystem; any use or integration in this project should be documented once it is actually implemented.

## Current Features

- Enter a question for the agents to consider.
- Add Agent A's claim and supporting evidence.
- Add Agent B's claim and supporting evidence.
- Display a result based on the entered claims and evidence.
- Highlight cases where evidence is missing or does not resolve a disagreement.

## Technology Stack

- Python
- Flask
- HTML and CSS (embedded in the Flask application)

## Requirements

- Python 3
- Flask

## Run Locally

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Install the dependency:

   ```bash
   python3 -m pip install -r requirements.txt
   ```

4. Start the application:

   ```bash
   python3 app.py
   ```

5. Open this address in your browser:

   ```text
   http://127.0.0.1:5001
   ```

## Project Status and Limitations

This is an early prototype. Its current result logic is rule-based and uses the claims and evidence entered into the form. It does **not** independently verify facts, run two autonomous AI agents, or complete an actual OMEGA framework integration yet. A displayed result should not be treated as a verified fact.

## Planned Improvements

- Integrate the OMEGA framework and document the integration.
- Add actual agent-to-agent reasoning and evidence comparison.
- Provide clearer explanations for disagreements and uncertainty.
- Add test cases for matching claims, conflicting claims, and missing evidence.
- Improve documentation and prepare a demonstration.

## Team

Built by the OMEGA TruthBridge hackathon team.

## License

No license has been selected yet. Add a license before allowing others to reuse or distribute the project.
