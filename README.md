# Income Tax Calculator FY 2025-26 (India)

A comprehensive, interactive Income Tax Calculator for Financial Year 2025-26 (Assessment Year 2026-27) for Indian taxpayers.

## Features

### 🎯 Core Functionality
- **Tax Regime Comparison**: Compare Old vs New tax regime side-by-side
- **Real-Time Calculation**: Instant tax updates as you type
- **Smart Recommendations**: Automatically suggests the better regime with potential savings
- **Comprehensive Inputs**: Multiple income sources and all major deductions

### 💰 Income Calculation
- Annual Gross Salary
- Basic Salary (for HRA calculation)
- Dearness Allowance (DA)
- Bonus / Variable Pay
- Other Income (Interest, Rental, etc.)

### 🏠 HRA Exemption (Old Regime)
Automatic calculation based on:
- HRA received
- Rent paid
- Basic salary + DA
- City type (Metro/Non-Metro)

### 📊 Deductions (Old Regime)
With automatic validation and caps:
- **Section 80C**: Investment deductions (max ₹1,50,000)
- **Section 80D**: Health insurance (max ₹25,000 or ₹50,000 for senior citizens)
- **Section 80CCD(1B)**: Additional NPS contribution (max ₹50,000)
- **Section 80E**: Education loan interest (no limit)
- **Section 24(b)**: Home loan interest (max ₹2,00,000)
- Other deductions

### 🎨 User Experience
- **Collapsible Sections**: Clean, organized interface
- **Tooltips**: Helpful explanations for tax terms
- **Mobile Responsive**: Works perfectly on all devices
- **Data Persistence**: Saves your inputs automatically
- **Visual Indicators**: Progress bars and color coding

## Tax Rates (FY 2025-26)

### New Tax Regime
- ₹0 - ₹4,00,000: 0%
- ₹4,00,001 - ₹8,00,000: 5%
- ₹8,00,001 - ₹12,00,000: 10%
- ₹12,00,001 - ₹16,00,000: 15%
- ₹16,00,001 - ₹20,00,000: 20%
- ₹20,00,001 - ₹24,00,000: 25%
- Above ₹24,00,000: 30%

**Standard Deduction**: ₹75,000  
**Section 87A Rebate**: Up to ₹25,000 (if taxable income ≤ ₹7,00,000)

### Old Tax Regime
- ₹0 - ₹2,50,000: 0%
- ₹2,50,001 - ₹5,00,000: 5%
- ₹5,00,001 - ₹10,00,000: 20%
- Above ₹10,00,000: 30%

**Standard Deduction**: ₹50,000  
**Section 87A Rebate**: Up to ₹12,500 (if taxable income ≤ ₹5,00,000)  
**Plus**: All deductions under Chapter VI-A

## How to Use

1. **Select Tax Regime**: Choose Old, New, or Compare Both
2. **Enter Income Details**: Fill in all income sources
3. **Configure HRA** (Old Regime): If applicable, check "I receive HRA" and enter details
4. **Add Deductions** (Old Regime): Enter all applicable deductions
5. **View Results**: Tax is calculated automatically in real-time
6. **Save Inputs**: Click "Save Inputs" to remember your data
7. **Compare**: Use "Compare Both" to see which regime saves you more

## Features in Detail

### Comparison Mode
- Side-by-side tax calculation for both regimes
- Automatic recommendation based on lower tax liability
- Shows exact savings amount
- Visual progress indicator

### Smart Validation
- Automatically caps deductions at legal limits
- Prevents invalid inputs
- Provides helpful hints and tooltips

### Data Persistence
- Saves all inputs to browser's localStorage
- Auto-loads saved data on page refresh
- Cleared only when you click "Reset All"

### Responsive Design
- Optimized for desktop, tablet, and mobile
- Collapsible sections for clean mobile experience
- Touch-friendly interface

## Technical Details

- **Pure JavaScript**: No frameworks or build tools required
- **Tailwind CSS**: Modern, responsive design via CDN
- **Client-Side Only**: No backend, no data sent to servers
- **GitHub Pages Ready**: Deploy instantly
- **Browser Compatibility**: All modern browsers

## Deployment

Simply open `index.html` in a web browser or host it on any static hosting service:

- GitHub Pages
- Netlify
- Vercel
- Any web server

No build process or dependencies installation required!

## Disclaimer

⚠️ **For Estimation Purposes Only**

This calculator provides estimates based on the tax rules for FY 2025-26. For accurate tax calculations and filing:
- Consult a Certified Chartered Accountant (CA)
- Refer to official Income Tax Department guidelines
- Consider your specific financial situation

## License

Free to use for personal tax estimation.

## Contributing

Found a bug or have a suggestion? Please open an issue or submit a pull request!

---

**Made with ❤️ for Indian taxpayers**
