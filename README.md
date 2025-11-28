# EPC QR Generator

A minimal static web app for generating [EPC QR codes](https://en.wikipedia.org/wiki/EPC_QR_code) — the European Payments Council standard for SEPA credit transfer QR codes.

## Usage

Open `index.html` in a browser. Fill in the payment details and click "Generate QR Code".

Form state syncs to the URL, so you can share or bookmark links with pre-filled data.

## Fields

- **Beneficiary Name** — Recipient name (required)
- **IBAN** — International Bank Account Number (required)
- **BIC** — Bank Identifier Code (optional, required for non-EEA)
- **Amount** — Payment amount in EUR (optional)
- **Reference** — Payment reference or remittance info (optional)

