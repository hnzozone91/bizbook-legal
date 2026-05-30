# BizBook Privacy Policy

**Last updated:** 2026-05-30  
**App:** BizBook — Invoice, POS & Inventory  
**Developer:** FieldHealth Africa  
**Contact:** hnzozone91.nh@gmail.com

---

## 1. What BizBook Is

BizBook is a business management application for small businesses. It stores business operations data including products, inventory, sales, invoices, expenses, supplier and client records, and staff attendance. It does **not** collect, store, or process any patient records, medical prescriptions, or clinical data.

## 2. Data We Collect and How We Use It

### 2a. Data You Enter (stored on your device)
The following data is stored locally on your device in a secure SQLite database:
- Business profile (name, address, logo, currency, tax settings)
- Products and inventory records
- Sales and invoice records
- Client and supplier contact information
- Expense records
- Staff names, roles, and attendance logs
- Payroll records

This data is yours. It never leaves your device unless you explicitly enable Cloud Sync (see §2b).

### 2b. Cloud Sync (Optional — requires sign-in)
If you choose to enable Cloud Sync, your business data listed in §2a is encrypted in transit (HTTPS/TLS) and stored in a Supabase-hosted PostgreSQL database. This enables multi-device access and automatic backups.

- **Authentication:** We use Supabase Auth (email/password). Your password is never stored in plain text.
- **Hosting:** Supabase servers may be located in the United States or European Union.
- **You can disable sync and delete cloud data** at any time from Settings → Backup & Sync → Delete Account.

### 2c. AI Features (Optional — requires credits)
If you use AI features (scan-to-inventory, invoice OCR, or the AI assistant):
- Images you photograph are compressed on-device and sent to our backend proxy
- The proxy calls the Anthropic Claude API to extract information
- Images are processed and **not stored permanently** on our servers
- Only the extracted text/data is returned to your device
- We log aggregate usage counts (not content) for billing purposes

### 2d. In-App Purchases
Subscription and credit pack purchases are handled entirely by **Google Play Billing** (Android) or **Apple StoreKit** (iOS). We receive only a confirmation of purchase, not your payment details. Google/Apple's privacy policies govern payment data.

### 2e. Camera Permission
The camera permission is used only for:
- Scanning barcodes/QR codes in the POS
- Photographing products for AI-assisted data entry
- Photographing supplier invoices for OCR

We do not access your camera gallery or store images from your personal photos.

### 2f. Analytics and Crash Reporting
We do **not** collect analytics. We do not use third-party trackers (no Google Analytics, Facebook SDK, etc.). Future versions may add opt-in crash reporting — if so, this policy will be updated.

## 3. Data Sharing

We do not sell, trade, or share your data with third parties, except:
- **Supabase** (cloud infrastructure provider) — only if you enable Cloud Sync
- **Anthropic** (AI processing) — only if you use AI features; images are processed and not retained
- **Google Play / Apple App Store** — for in-app purchase verification only

## 4. Data Retention and Deletion

**Local data:** Stored on your device until you use Settings → Delete Account, or uninstall the app.

**Cloud data:** Stored until you delete your account from Settings → Delete Account, which removes all cloud data within 30 days.

**To request data deletion**, use Settings → Delete Account within the app, or email: hnzozone91.nh@gmail.com

## 5. Security

- All data in transit is encrypted using HTTPS/TLS
- Cloud data is protected by Supabase Row Level Security (RLS) policies
- PIN lock and biometric authentication are available to protect local app access
- Your Anthropic API key is **never** stored in the app — it lives only on our secure server

## 6. Children's Privacy

BizBook is a business application intended for adults (18+). We do not knowingly collect data from children under 13. If you believe a child has provided information through our app, contact us at hnzozone91.nh@gmail.com.

## 7. Changes to This Policy

We may update this Privacy Policy. When we do, we will update the "Last updated" date above. Continued use of the app after changes constitutes acceptance of the updated policy.

## 8. Contact

FieldHealth Africa  
Email: hnzozone91.nh@gmail.com  
App: BizBook — Invoice, POS & Inventory

---
*This privacy policy was last updated on 2026-05-30.*
