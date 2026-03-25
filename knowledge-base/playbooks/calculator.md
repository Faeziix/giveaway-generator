# Calculator Playbook

## What It Is
A calculator is an interactive tool -- typically a spreadsheet or web-based form -- that takes user inputs and returns personalized outputs based on formulas or data models. It transforms abstract concepts (like ROI, profitability, or capacity) into concrete, specific numbers that the user can act on immediately. The personalization is what makes it sticky.

## When to Use It
- **Buyer stage:** Mid-funnel (consideration) and bottom-funnel (decision)
- **Best industries:** E-commerce, SaaS, agencies, financial services, any business where numbers drive decisions
- **Taxonomy categories:** Enable
- **Use when:** Your audience needs to make a decision that depends on their specific numbers, you want to surface a problem they did not know they had (diagnostic calculators), or you want to demonstrate value by showing the gap between current and potential performance

## Anatomy of a Good Calculator
- **Input section:** Clearly labeled fields with helper text explaining what to enter and where to find the data. Use dropdowns or sliders where possible to reduce friction.
- **Calculation logic:** Hidden or protected formulas that do the math. The user should never need to understand the formulas -- they just enter inputs and get outputs.
- **Output/results section:** A clear summary of the results with visual formatting (bold numbers, color coding for good/bad ranges, charts if appropriate).
- **Interpretation guide:** A section explaining what the results mean in plain language. "If your number is X, that means Y, and you should do Z."
- **Instructions tab:** A separate tab or section explaining how to use the calculator, what assumptions it makes, and any limitations.
- **Design:** Professional formatting, locked cells for formulas, input cells highlighted with a distinct color.

## Step-by-Step Creation Process
1. **Identify the decision** -- What specific decision does your audience need to make that requires math? The best calculators help people answer a question they already have (e.g., "Can I afford to scale?" or "What is my true ROAS?").
2. **Map the formula** -- Write out the complete calculation on paper first. Identify every input variable, every formula step, and every output. Test the math with real numbers before building anything.
3. **Build the input section** -- Create clearly labeled fields for each input. Add helper text, example values, and data source suggestions. Make it impossible to enter invalid data (use data validation).
4. **Build the calculation engine** -- Implement the formulas in a protected area. Use named ranges for clarity. Build in error handling for edge cases (division by zero, negative values, etc.).
5. **Design the output** -- Present results in a way that drives action. Use conditional formatting (green/yellow/red), comparison charts, and plain-language summaries. Always answer "so what?" for the user.
6. **Name it** -- Apply naming conventions from naming-conventions.md. Name it after the outcome, not the math.
7. **Package and deliver** -- Google Sheets is ideal (easy to share, auto-saves). Lock all cells except input fields. Include a "Make a Copy" instruction prominently. Consider also building a simple web version for higher perceived value.

## Naming Tips
- **Formula 1:** "[Metric] Calculator" -- e.g., *ROAS Calculator & Bottleneck Finder*
- **Formula 2:** "[Outcome] Forecaster" -- e.g., *Gross Profit Forecaster*
- **Formula 3:** "The [Audience] [Metric] Calculator" -- e.g., *The DTC Brand Profitability Calculator*

See naming-conventions.md for full naming guidelines.

## Linear Examples
- **Gross Profit Forecaster** -- Works because "forecaster" implies forward-looking value (not just reporting what happened), and gross profit is a metric every e-commerce brand cares about.
- **ROAS Calculator & Bottleneck Finder** -- Works because it combines a standard calculator with a diagnostic element ("bottleneck finder"), adding a layer of insight beyond raw numbers.

## Effort Estimate
- **Time to create:** 4-12 hours (depending on formula complexity and design polish)
- **Skills needed:** Spreadsheet formulas, data modeling, basic UX thinking for input/output design
- **Maintenance:** Periodic updates (formulas may need adjustment as industry benchmarks change, platform metrics evolve, or users report edge cases)
