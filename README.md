# Minutes Prompt Generator

A lightweight, standalone browser tool that creates a structured prompt for generating accurate meeting minutes with an AI assistant.

The tool does **not** collect or process meeting transcripts. It prepares the meeting context and workflow instructions, then asks the AI assistant to:

1. Request the user's notes or transcript
2. Extract key information
3. Pause for user verification
4. Generate the final meeting minutes only after approval

## Live Demo

After enabling GitHub Pages, add your link here:

`https://YOUR-USERNAME.github.io/minutes-prompt-generator/`

## Key Features

- Clear five-step onboarding screen
- Mandatory meeting topic, date, time, venue, and attendees
- Optional project, chairperson, meeting type, language, and style settings
- High-contrast controls and visible selection states
- Recommended accuracy controls enabled by default
- Multi-part transcript workflow using `SOURCE COMPLETE`
- Verification stage before final minutes are generated
- Copy and text-download feedback
- Responsive desktop and mobile layout
- No server, API, analytics, external font, or external library
- Runs locally as one HTML file

## How It Works

1. Open the tool.
2. Enter the essential meeting details.
3. Select the preferred minutes style and workflow options.
4. Generate and copy the prompt.
5. Paste the prompt into your preferred AI assistant.
6. Provide the notes or transcript directly to the AI assistant.
7. Verify the extracted information.
8. Approve the extraction to generate the final minutes.

## Privacy

The generator runs entirely in the browser. It does not upload, transmit, or store meeting information. The generated prompt can be copied or downloaded locally.

Meeting notes and transcripts should be submitted directly to an AI service selected and approved by the user or their organisation. Users remain responsible for following their organisation's confidentiality, information-security, and AI-use requirements.

## Use Locally

Download `index.html` and open it in a modern web browser. No installation or internet connection is required.

## Publish with GitHub Pages

1. Create a public repository named `minutes-prompt-generator`.
2. Upload all files from this repository package.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder.
6. Save the settings.
7. Replace the placeholder under **Live Demo** with the published URL.

## Repository Structure

```text
.
├── index.html
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── SECURITY.md
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── .gitignore
└── .nojekyll
```

## Accessibility

The interface uses high-contrast selected states, written validation messages, keyboard focus indicators, semantic labels, responsive layouts, and status feedback for major actions.

## Contributing

Suggestions and improvements are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## Security

Please report potential security or privacy issues using the process described in [SECURITY.md](SECURITY.md).

## License

Released under the [MIT License](LICENSE).
