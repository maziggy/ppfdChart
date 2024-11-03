# ppfdChart

A custom dashboard card for Home Assistant that shows a bar chart that displays the current ppfd value for grow lights.

## Installation

### Via HACS

1. Ensure you have [HACS](https://hacs.xyz/) installed.
2. In Home Assistant, go to **HACS** > **Frontend**.
3. Click the **"+"** button to add a new repository.
4. Enter the repository URL: `https://github.com/maziggy/ppfdChart.git`.
5. Select **Dashboard** as the category and **Save**.
6. Once installed, add the card to your Lovelace dashboard.

## Configuration

```yaml
type: custom:ppfd-custom-card
entity: input_number.grow_ppfd
refresh_interval: 60 # seconds

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=Martin+Ziegler&repository=https%3A%2F%2Fgithub.com%2Fmaziggy%2FppfdChart.git&category=Dashboard)

## Screenshot
[![Screenshot](https://raw.githubusercontent.com/maziggy/ppfdChart/refs/heads/main/images/ppfdChart.png)](https://raw.githubusercontent.com/maziggy/ppfdChart/refs/heads/main/images/ppfdChart.png)

