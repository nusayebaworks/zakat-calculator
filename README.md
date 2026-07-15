# 🕌 Zakat Calculator & Tracker

A modern, privacy-first zakat calculator and tracking application built as a progressive web app (PWA).

## Features

### Free Plan
- **Full Zakat Calculator** – Calculate zakat on diverse asset types (cash, gold, silver, business inventory, stocks, RSUs, crypto, and more)
- **Hawl Date Tracking** – Track the lunar year (hawl) completion date for your zakatable wealth
- **1 Saved Calculation** – Store and revisit one calculation locally

### Plus Plan ($18/year)
- **Unlimited History** – Save unlimited calculation records
- **Hawl Email Reminders** – Get notified before your hawl date completes
- **PDF Receipt Export** – Export calculations as shareable receipts

### Pro Plan ($40/year)
- **Everything in Plus**
- **Multi-Year Zakat Trend Chart** – Visualize your zakat trends over time
- **Multi-Profile Support** – Track zakat for business and family wealth separately
- **Priority Scholar Q&A Access** – Get guidance on edge cases directly from qualified scholars

## How It Works

### Nisab Basis
Choose between **silver** (612.36g) or **gold** (87.48g) as your nisab reference, then input current spot prices per gram in your local currency.

### Asset Categories
- **Liquid Assets** – Cash, gold, silver
- **Business & Investments** – Inventory, trading stocks, long-term holdings, RSUs, crypto
- **Receivables & Rental** – Money owed to you, unspent rental income
- **Liabilities** – Debts and bills due within 12 months

### Calculation
- Total zakatable assets − Liabilities = Net zakatable wealth
- If net wealth ≥ nisab threshold, zakat due = 2.5% of net wealth
- Tracks hawl date from when wealth first reached nisab

### Privacy & Storage
All data is stored locally on your device using browser storage. No data is transmitted to servers unless you explicitly enable email reminders (Plus feature).

## Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript
- **PWA:** Web Manifest + Service Worker for offline support
- **Storage:** Browser localStorage for profile, history, and settings
- **Styling:** CSS custom properties (dark theme optimized for readability)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/nusayebaworks/zakat-calculator.git
   cd zakat-calculator
   ```

2. Serve locally (requires a simple HTTP server):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. Open `http://localhost:8000` in your browser

4. **Install as PWA:**
   - On mobile: Tap the share menu → "Add to Home Screen"
   - On desktop: Click the install icon in the address bar

## Disclaimer

This tool provides a calculation aid based on standard fiqh positions (2.5% rate, silver/gold nisab). **Not a fatwa.** Confirm business/RSU edge cases and any specific circumstances with a qualified Islamic scholar in your area.

## Future Enhancements

- Backend integration for payment processing (Stripe halal-compliant setup)
- Email reminder system
- Multi-profile management UI
- Trend charts and analytics dashboard
- Scholarly Q&A system
- Multi-language support

## License

MIT License – See LICENSE file for details

## Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

## Support

For issues, questions, or suggestions, please open an [issue](https://github.com/nusayebaworks/zakat-calculator/issues) on GitHub.

---

**Built with ❤️ for the Muslim community**