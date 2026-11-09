# Data policy

This repository is public. Everything in it follows these rules:

1. **Synthetic data only.** No real company, customer, supplier, shipment, booking, container or PO data.
2. **No employer internals.** No internal system names, URLs, tenant or environment IDs, SharePoint site paths or screenshots of internal tools.
3. **No secrets.** API keys, tokens and passwords live in environment variables or connection references, never in flow definitions, code or screenshots.
4. **No personal data.** No names, emails or phone numbers of real people in test data or screenshots.
5. **Exported solutions are checked before commit:** open the .zip, search for keys, URLs and emails, and remove anything that breaks rules 1–4.

If something here looks like it breaks these rules, please open an issue.
