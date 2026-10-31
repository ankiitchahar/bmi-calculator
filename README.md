# BMI Calculator

A lightweight, web-based BMI calculator built with HTML, CSS and JavaScript. Enter your height and weight to get your Body Mass Index, its category, and a short health message, all in the browser with no server or database.

## Features

- Calculates BMI from height (cm) and weight (kg), rounded to one decimal place
- Classifies the result as Underweight, Normal Weight, Overweight or Obese using WHO adult ranges
- Colour-coded scale that highlights your category
- Five ordered input checks: empty, non-numeric, zero or negative, unrealistic height (50-300 cm), unrealistic weight (above 500 kg)
- Clear error messages with a shake animation
- Calculate and Reset buttons, plus Enter key support
- Responsive layout down to 480 px phones
- Fully client-side: no personal data is stored or transmitted

## BMI Categories

| Category      | BMI (kg/m²) |
|---------------|-------------|
| Underweight   | Below 18.5  |
| Normal Weight | 18.5 - 24.9 |
| Overweight    | 25 - 29.9   |
| Obese         | 30 and above |

Formula: `BMI = weight (kg) / (height (m))²`

## Tech Stack

- **HTML5** (`index.html`): page structure
- **CSS3** (`style.css`): styling, animations, responsive layout
- **JavaScript** (`script.js`): validation, calculation, classification, DOM updates

## Project Structure

```
├── index.html
├── style.css
└── script.js
```

## Testing

The calculation and validation logic was verified against 12 test cases covering normal, boundary (18.5, 25.0, 30.0) and invalid inputs. All passed.

## Limitations

- Metric units only (cm and kg)
- Intended for adults; not a medical diagnosis
- BMI does not distinguish muscle from fat
- Uses a single set of cut-offs (no region-specific ranges)

## Future Scope

Unit conversion (ft/in, lbs), age- and gender-based guidance, region-specific cut-offs, BMI history in the browser, and screen-reader support.

## Disclaimer

This tool is a general screening aid and not a substitute for professional medical advice. Consult a doctor for health decisions.

## Author

Ankit Chahar, MCA (Sem I), University Institute of Computing, Chandigarh University
Guide: Ms. Saranjeet Kaur

Supports UN Sustainable Development Goal 3: Good Health and Well-being.
