# RentPay

RentPay is a responsive, single-page frontend prototype for managing rental and property payments. It brings rent, society maintenance, utility bills, checkout, and receipt previews together in one demo interface.

> **Prototype notice:** This project is a frontend demonstration. Sign-in, payment verification, and payment processing are simulated in the browser. It does not connect to a payment gateway, bank, or backend, and its sample receipts are not official tax or payment documents. Do not enter real payment or personal information.

## Features

- Responsive home page with a quick payment entry point.
- Rental and property service catalog with category filters.
- Cart with item removal, fee/tax summary, and promo codes (`ZEROFEES` and `WELCOME`).
- Demo payment screen with UPI, card, and net banking options.
- Bill ledger with pending/paid views and demo payment flow.
- Printable receipt layout with a print / save-as-PDF action.
- Demo account access, contact form feedback, mobile navigation, and toast notifications.

## Built with

- HTML
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Font Awesome (CDN)
- Google Fonts (Inter and Plus Jakarta Sans)

## Run locally

No build step or package installation is required.

1. Clone or download this repository.
2. Open `project.html` in a modern web browser.
3. For a local web server, you can use the VS Code **Live Server** extension and open `project.html`.

The Tailwind CSS, fonts, and icons are loaded from external CDNs, so an internet connection is needed for those assets.

## Project structure

```text
.
├── project.html   # Application markup, styles, and demo JavaScript
└── README.md      # Project overview and setup instructions
```

## Current limitations

- Application data and account details are sample data defined in the page.
- User authentication and UPI verification are simulated; no identity checks occur.
- Payments are simulated and do not transfer money.
- Data is not connected to a server or persistent database.
- The demo should not be used to make real payments or to generate official receipts.

## Possible next steps

- Add a backend API and persistent storage.
- Integrate a payment provider in a secure, compliant environment.
- Replace demo authentication with a production identity solution.
- Add automated tests and deployment configuration.

## License

No license is currently specified for this project. Add a `LICENSE` file before redistributing it under an open-source license.
