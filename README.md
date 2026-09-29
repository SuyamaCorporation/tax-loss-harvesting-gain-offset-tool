# Tax-Loss Harvesting Capital Gain Offset Tool

Model how harvested investment losses offset short and long-term capital gains to reduce annual tax liability, following IRS netting rules.

## Features
- Configure short-term, long-term, NIIT, and state tax rates
- Add multiple loss positions with symbol, amount, and type (ST/LT)
- IRS-compliant offset waterfall: ST losses offset ST gains first, then LT gains
- Visual before/after tax comparison chart
- Carryover loss calculation for future years
- Wash sale rule reminder
- localStorage save/load

## Usage
Enter your capital gains and tax rates, then add harvested loss positions. Click "Calculate Tax Impact" to see how losses reduce your tax bill and what carries forward.

## Tech
- Tailwind CSS CDN
- Chart.js CDN
- Vanilla JS
- localStorage
