# BRNNO Services - Mobile Auto Detailing Booking System

A complete HTML booking flow for mobile auto detailing services.

## 🚀 Quick Deploy to Vercel

1. **Push to GitHub** (if not already there)
2. **Connect to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Deploy!

## 📁 Project Structure

```
brnno-services/
├── location.html      # Start here - Location entry
├── service.html       # Service selection
├── results.html       # Available detailers
├── schedule.html      # Time scheduling
├── payment.html       # Payment form
├── confirmation.html  # Booking confirmation
├── styles.css         # Main styles
├── flow.css          # Booking flow styles
├── BRNNO_logov3.jpg  # Logo
├── vercel.json       # Vercel configuration
└── package.json      # Project metadata
```

## 🔧 Setup Instructions

### For Stripe Payments:
1. Create account at [stripe.com](https://stripe.com)
2. Get your publishable key from Stripe Dashboard → API Keys
3. Replace `YOUR_STRIPE_PUBLISHABLE_KEY` in `payment.html` line 106
4. Set up webhook for payment processing (optional)

### For Custom Domain:
1. Add domain in Vercel dashboard
2. Update DNS records as instructed
3. SSL certificate is automatic

## 🌐 Live URLs

After deployment, your booking flow will be available at:
- `https://your-project.vercel.app/` → Location page
- `https://your-project.vercel.app/service` → Service selection
- `https://your-project.vercel.app/results` → Available detailers
- `https://your-project.vercel.app/schedule` → Time scheduling
- `https://your-project.vercel.app/payment` → Payment form
- `https://your-project.vercel.app/confirmation` → Booking confirmation

## 📱 Features

- ✅ **Mobile-responsive** design
- ✅ **Complete booking flow** (6 pages)
- ✅ **Professional styling** with BRNNO branding
- ✅ **Stripe payment integration** ready
- ✅ **Back button navigation** throughout flow
- ✅ **Pricing logic** built-in
- ✅ **No backend required** for basic functionality

## 🛠️ Customization

- **Pricing:** Edit the pricing logic in `payment.html` (lines 132-146)
- **Services:** Modify service options in `service.html`
- **Styling:** Update `styles.css` and `flow.css`
- **Branding:** Replace `BRNNO_logov3.jpg` with your logo

## 📞 Support

This is a static HTML site that works immediately after deployment. No complex setup required!
