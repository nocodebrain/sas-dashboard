# SAS Connect Financial Dashboard

Real-time cost tracking and breakeven analysis for SAS Connect.

## Features

- 📊 **Real-time calculations** - Instant updates as you adjust values
- 👥 **User tier pricing** - Admin ($17), Supervisor ($15), Crew ($8) per month
- 📈 **Add-on modules** - Analytics ($129) & Social Procurement ($59) with conversion tracking
- 💰 **Cost breakdown** - Infrastructure, variable costs, salaries, marketing
- 🎯 **Breakeven graph** - Visual chart showing profitability at different scales
- 💎 **Key metrics** - Revenue per user, cost per user, profit margin

## Usage

Simply open the dashboard and adjust the input fields:

1. **User Counts** - Set your current or projected user numbers
2. **Pricing** - Adjust subscription prices per user tier
3. **Add-ons** - Set pricing and conversion rates for additional modules
4. **Monthly Costs** - Update infrastructure, salaries, and operational costs

All calculations update automatically. The breakeven chart shows when you hit profitability as you scale.

## Deployment

### Railway
Deploys automatically from GitHub. Just push to main branch.

### Local
```bash
npm install
npm start
```

Then open http://localhost:3000

## Tech Stack

- Pure HTML/CSS/JavaScript
- Chart.js for visualizations
- Express.js for serving (production)
- No database required - all calculations client-side

## License

MIT
