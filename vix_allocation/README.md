# VIX Price Levels Indicator

A Pine Script indicator designed specifically for the VIX (Volatility Index) that displays color-coded price level zones and customizable text labels to help you quickly identify which price range the VIX is currently trading in.

## Features

- **6 Price Level Zones**: Visual color-coded regions covering the entire VIX price range
  - Level 1: 0-12 (Blue)
  - Level 2: 12-15 (Purple)
  - Level 3: 15-20 (Green)
  - Level 4: 20-25 (Yellow)
  - Level 5: 25-30 (Orange)
  - Level 6: 30+ (Red)

- **Customizable Text Labels**: Add your own text annotations for each level
- **Current Price Indicator**: Shows which level the current price is in
- **VIX-Only Display**: Automatically only displays on VIX charts
- **Horizontal Boundary Lines**: Clear visual markers at each level boundary

## Installation Instructions

### Step 1: Open TradingView Pine Editor

1. Go to [TradingView.com](https://www.tradingview.com) and log in to your account
2. Open any chart (preferably a VIX chart)
3. Click on **"Pine Editor"** at the bottom of the screen (or press `Alt + E`)

### Step 2: Create a New Indicator

1. In the Pine Editor, click the **"New"** button (or `Ctrl + N`)
2. Delete any default code that appears in the editor

### Step 3: Copy the Script

1. Open the `price_levels.pine` file
2. Select all the code (`Ctrl + A`)
3. Copy it (`Ctrl + C`)
4. Paste it into the TradingView Pine Editor (`Ctrl + V`)

### Step 4: Save and Add to Chart

1. Click the **"Save"** button (or `Ctrl + S`)
2. Give your script a name (e.g., "VIX Price Levels")
3. Click **"Add to Chart"** button (or `Ctrl + Enter`)

The indicator will now appear on your chart!

## Configuration

### Accessing Settings

1. Click on the indicator name in the chart legend (top left)
2. Click the **gear icon** ⚙️ to open settings
3. Navigate to the **"Inputs"** tab

### Setting Up Level Text Labels

In the **"Level Labels"** section, you can:

- **Level 1 (0-12) Text**: Enter text for the first level (e.g., "Low Volatility")
- **Level 2 (12-15) Text**: Enter text for the second level (e.g., "Moderate")
- **Level 3 (15-20) Text**: Enter text for the third level (e.g., "Elevated")
- **Level 4 (20-25) Text**: Enter text for the fourth level (e.g., "High")
- **Level 5 (25-30) Text**: Enter text for the fifth level (e.g., "Very High")
- **Level 6 (30+) Text**: Enter text for the sixth level (e.g., "Extreme Fear")

### Text Display Options

- **Text Position**: Choose where labels appear
  - **Left**: Labels appear on the left side of the chart
  - **Right**: Labels appear on the right side of the chart (default)
  - **Center**: Labels appear in the center

- **Show Level Text**: Toggle to show/hide all level text labels

### Style Settings

In the **"Style"** tab, you can customize:
- Line colors for each level boundary
- Fill colors and transparency for each level zone
- Label colors and sizes

## Usage Tips

1. **VIX Charts Only**: This indicator automatically detects VIX charts. It will not display on other symbols.

2. **Understanding the Levels**:
   - The colored zones make it easy to see at a glance which volatility range you're in
   - Each level represents a different market sentiment zone
   - The current price indicator shows exactly which level the VIX is trading in

3. **Custom Labels**: Use the text labels to add your own trading notes, such as:
   - Entry/exit points
   - Support/resistance levels
   - Trading strategies for each level
   - Historical significance

4. **Multiple Timeframes**: The indicator works on all timeframes, from 1-minute to monthly charts.

## Troubleshooting

### Indicator Not Showing

- **Check Symbol**: Make sure you're viewing a VIX chart (VIX, VIX1!, VIX9D, etc.)
- **Check Chart Type**: Ensure you're on a regular candlestick/line chart (not Renko, Point & Figure, etc.)
- **Refresh**: Try removing and re-adding the indicator

### Text Labels Not Visible

- **Check Settings**: Go to Inputs → Level Labels → Make sure "Show Level Text" is enabled
- **Add Text**: Text labels only appear if you've entered text in the settings
- **Check Position**: Try changing the "Text Position" setting

### Lines Not Showing

- **Check VIX Symbol**: The indicator only works on VIX-related symbols
- **Zoom Out**: Make sure your chart is zoomed to show the price range (0-40+)

## Technical Details

- **Pine Script Version**: v5
- **Indicator Type**: Overlay (displays on price chart)
- **Compatibility**: Works with all TradingView chart types that support overlays

## Support

If you encounter any issues or have suggestions for improvements, please check:
- TradingView Pine Script documentation: https://www.tradingview.com/pine-script-docs/
- Pine Script v5 Reference Manual: https://www.tradingview.com/pine-script-reference/v5/

## License

This script is provided as-is for personal use. Feel free to modify and customize it for your trading needs.

---

**Happy Trading! 📈**

