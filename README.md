# Arabic-English Alignment Fixer

A lightweight browser-based tool that improves the display
of mixed Arabic and English text.

It helps keep English phrases and numbers in their intended
left-to-right order within Arabic text.

## Features

- Process mixed Arabic and English text.
- Isolate English phrases and numbers using Unicode direction controls.
- Apply right-to-left direction to each line.
- Preview results automatically while typing.
- Copy the processed text.
- Run offline without installation or external dependencies.
- Adapt to the device's light or dark appearance.

## Getting Started

1. Select Code → Download ZIP.
2. Extract the downloaded ZIP file.
3. Open index.html in your browser.
4. Paste your mixed Arabic and English text.
5. Review the result and click Copy fixed text.

If automatic copying is unavailable, the tool selects the result.
Press Ctrl+C on Windows or Cmd+C on Mac to copy it.

## Options

### Live

Update the preview automatically while typing.
When disabled, click Fix alignment to process the text.

### Force each line RTL

Apply right-to-left direction to every non-empty line.

When disabled, only lines containing Arabic characters
receive the right-to-left wrapper.

## How It Works

The tool removes existing directional control characters,
then adds Unicode isolation controls around detected English
and number phrases.

Arabic-containing lines are wrapped in right-to-left isolation.
The optional force setting applies this to every non-empty line.

Line breaks are preserved.

## Privacy

Text is processed locally in your browser.
The application does not send text to a server or save it
in browser storage.

## Limitations

Results depend on how the destination application handles
Unicode bidirectional text.

The copied result contains invisible direction controls.
Use it for readable text, rather than executable code,
passwords, or other inputs requiring exact characters.

The tool adjusts text direction. It does not translate text,
correct spelling, or change document layout.

## Technology

- HTML
- CSS
- JavaScript
- Unicode bidirectional isolation controls

## Updates

Replace index.html with the latest version.
Use descriptive commit messages to record changes.
