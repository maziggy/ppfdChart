# ppfdChart

A custom Lovelace card for Home Assistant that shows a bar chart that displays the current ppfd value for grow lights.

## Installation

### Via HACS

1. Ensure you have [HACS](https://hacs.xyz/) installed.
2. In Home Assistant, go to **HACS** > **Frontend**.
3. Click the **"+"** button to add a new repository.
4. Enter the repository URL: `https://github.com/maziggy/ppfdChart.git`.
5. Select **Lovelace** as the category and **Save**.
6. Once installed, add the card to your Lovelace dashboard.

## Configuration

```yaml
type: custom:ppfd-custom-card
entity: input_number.grow_ppfd
refresh_interval: 60 # seconds

## Screenshot
[![Screenshot](https://raw.githubusercontent.com/maziggy/ppfdChart/refs/heads/main/images/ppfdChart.png)]
