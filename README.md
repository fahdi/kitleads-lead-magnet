# KitLeads – Grand Slam Lead Magnets for Kit.com

**KitLeads** is the ultimate tool for creators who want to build high-converting audiences. Deploy **Grand Slam Lead Magnets** and capture **Qualified Leads** directly into your Kit.com (ConvertKit) account with zero friction.

## 🚀 The Strategic Advantage

- **Value-First Lead Generation:** Offer massive value upfront to build trust and authority.
- **Grand Slam Magnets:** Optimized form layouts designed for high conversion and low friction.
- **Qualified Leads:** Sync high-intent subscribers directly to your Kit.com sequences.
- **Zero Friction:** AJAX-powered submissions mean no page reloads, keeping users in your content loop.
- **Fail-Safe Delivery:** Our "Data Resilience" bridge ensures you never lose a single lead, even if the API connection hiccups.

## 🛠️ Installation

1. Upload the `kit-leads-for-wp` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to **Settings > KitLeads Magnets** to configure your API Secret and Magnet ID.

## 📄 Usage

Use the following shortcode to drop your lead magnet anywhere:

```text
[kitleads]
```

**Attributes (Customize Your Offer):**
- `form_id`: Override the default magnet ID.
- `title`: Your compelling headline.
- `button_text`: The call to action (e.g., "Claim This Offer").
- `placeholder`: Where to send the value.

Example:
```text
[kitleads title="Get The Strategic Checklist" button_text="I Want This!"]
```

## 🔒 Security

- Protected by WordPress nonces.
- Server-side proxy keeps your API Secret hidden from the public.
- Sanitized data ensuring high-quality, safe lead capture.
