# Install and use PlacementPilot AI V5

PlacementPilot AI is distributed as a `.skill` package. You need an AI platform that explicitly supports importing this skill format.

## 1. Download the package

1. Visit the [PlacementPilot AI GitHub repository](https://github.com/mowlijamr/PlacementPilot-AI).
2. Open `placementpilot-ai_v5.skill`.
3. Use GitHub's **Download raw file** control to save the package to your device.

Direct download:
[Download placementpilot-ai_v5.skill](https://github.com/mowlijamr/PlacementPilot-AI/raw/refs/heads/main/placementpilot-ai_v5.skill)

## 2. Import it into a compatible AI platform

1. Open your AI platform's settings or skills/customization area.
2. Find the platform's skill import or upload workflow.
3. Upload the downloaded `placementpilot-ai_v5.skill` file.
4. Enable the skill if the platform requires activation.

**Important:** Import workflows differ between platforms and can change. Follow the current official instructions for your platform. A `.skill` package is not a universal plugin and will not automatically install in every AI assistant. The package's included README describes the Claude Skills upload-and-enable workflow; do not assume ChatGPT accepts the archive as a native skill.

## 3. Start your first session

After the skill is enabled, open a new chat and send:

```text
Start my placement preparation. Ask me the onboarding questions and help me create a personalized roadmap.
```

The skill will guide you through a one-time profile questionnaire. It asks for separate self-assessed levels in:
- Aptitude
- Technical
- Communication
- Interview

It will also ask about your branch, target role/domain, skills you already know, skills you want to learn, and available preparation time.

## 4. Use it regularly

Try these natural-language requests:

- `What should I learn today?`
- `Daily Practice`
- `Aptitude Practice`
- `Technical Practice`
- `Communication Practice`
- `Mock Interview`
- `My Progress`
- `Revise Mistakes`
- `Save Progress`

At the end of a session, ask for or use the portable progress snapshot. Keep it somewhere safe and paste it into a future chat when you want to resume. The skill does not store progress in a shared database or send background reminders.

## 5. Personalized PDF guide

The skill can generate a study-guide PDF when its script is run in an environment with Python and ReportLab. PDF generation is not guaranteed in every chat platform. Its PDF text supports Latin script; regional-language explanations can be provided in chat.

## Privacy and safety

Share only information needed for placement preparation. Do not enter passwords, government ID numbers, or other sensitive credentials. Do not use AI assistance to cheat in a live assessment or bypass proctoring.
