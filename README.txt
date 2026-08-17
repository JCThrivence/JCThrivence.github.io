PROJECT PRICING TOOL - PROTOTYPE V5

WHAT'S NEW
- Real resource roster is loaded from encrypted resource data generated from Resources.xlsx.
- The spreadsheet itself is NOT included in the distributed ZIP.
- A password is required to unlock the tool. The password is not stored in the HTML/JS/JSON.
- Cost rates are decrypted only in browser memory and are never written to project JSON or localStorage.
- Gross margin is now calculated after unlock.
- Export Report / PDF creates a clean internal pricing report using the browser Print dialog. Choose "Save as PDF" as the printer/destination.
- Billing-rate sliders remain synchronized with typed values and allow out-of-range overrides.

HOW TO USE
1. Extract the ZIP.
2. Double-click index.html in Microsoft Edge or Chrome.
3. Enter the pricing-data password supplied by your pricing administrator.
4. Define phases, add project resources, and allocate hours/week.
5. Use Export Report / PDF to create the pricing report.
6. Use Save Project JSON to preserve project planning data without consultant cost rates.

SECURITY NOTE
This prototype meaningfully protects cost rates at rest inside the distributed ZIP, but it is still a local browser application. A user who knows the pricing-data password and has advanced browser-debugging skills could potentially inspect decrypted values while the tool is running. The planned SharePoint deployment will provide a stronger authentication/security boundary.

SESSION BEHAVIOR
- The pricing tool starts with a new blank project every time it is opened or refreshed.
- Project data is not auto-saved to browser local storage.
- Use Save Project to export a project JSON if you want to continue it later, then use Open Project to reload it.
