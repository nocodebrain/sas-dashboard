# SAS Connect Financial Dashboard

Real-time cost tracking and breakeven analysis for SAS Connect workforce management platform.

## Features

### 📊 Complete Cost Management
- **Infrastructure** - Azure Server, Weather API, Auth0, SendGrid (all individually editable)
- **Dev Tools** - IntelliJ licenses, AI tools (Copilot), QA servers
- **Variable Costs** - Cost per system user tracking
- **Operational** - Salaries, marketing, other ops costs

### 👥 User Tracking
- **System Users** - Total users on the platform (billable + free)
- **Billable Users** - Admin ($17), Supervisor ($15), Crew ($8) per month
- **Free Users** - Automatically calculated
- **User Metrics** - Cost per system user, cost per billable user

### 📈 Revenue Modeling
- **Base Subscriptions** - Tiered pricing by user role
- **Add-on Modules** - Analytics ($129) & Social Procurement ($59)
- **Conversion Tracking** - Adjustable conversion rates for add-ons

### 💎 Analytics & Insights
- Real-time profit/loss calculations
- Profit margin tracking
- Revenue per billable user
- Cost per user (system + billable)
- Breakeven chart showing profitability at scale

## Default Values (from actual data)

**Users:**
- 1,000 total system users
- 750 billable (50 admin, 100 supervisors, 600 crew)
- 250 free users

**Infrastructure:**
- Azure Server: $3,000/month
- Weather API: $7/month
- Auth0: $240/month
- SendGrid: $20/month

**Dev Tools:**
- IntelliJ: $60/month
- AI Tools: $100/month
- QA Servers: $0 (configurable)

**Variable:**
- $0.50 per system user

**Operational:**
- Salaries: $0 (set your team costs)
- Marketing: $0 (set your growth budget)
- Other Ops: $0 (miscellaneous)

## Usage

1. **Adjust user counts** - Set current or projected users
2. **Update costs** - Every line item is editable
3. **Model pricing** - Test different price points
4. **Watch breakeven** - Chart shows profitability at scale

All calculations update instantly. No save button needed.

## Deployment

### Railway (Automatic)
Push to `main` branch → Railway auto-deploys

### Local Development
```bash
npm install
npm start
# Open http://localhost:3000
```

### Static Hosting
The `index.html` file is fully standalone - works with zero backend. Can be hosted on:
- Vercel
- Netlify
- GitHub Pages
- Any static host

## Tech Stack

- **Frontend:** Vanilla HTML/CSS/JavaScript
- **Charts:** Chart.js
- **Server:** Express.js (for production hosting only)
- **Data:** Client-side only (no database, all calculations in-browser)

## Customization

Edit `index.html` to:
- Add new cost categories
- Adjust default values
- Change pricing tiers
- Modify chart appearance
- Add new calculations

## License

MIT

---

Built for SAS Connect by OpenClaw
