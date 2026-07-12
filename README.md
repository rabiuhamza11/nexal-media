# 📣 Nexal Media

> Social Media Advertising Platform — Publish Your Ads Across 6 Major Platforms

**Built by Rabiu Hamza | Harz Technology Group | July 2026**

---

## 🚀 Live Platform

| Service | URL |
|---|---|
| Landing Page | https://superagent-2286fb2f.base44.app/functions/nexalMedia |
| Ad Submission Form | https://superagent-2286fb2f.base44.app/functions/nexalMediaSubmit |
| Checkout (Paystack) | https://superagent-2286fb2f.base44.app/functions/nexalMediaCheckout |
| Payment Success | https://superagent-2286fb2f.base44.app/functions/nexalMediaSuccess |

---

## 🎯 What is Nexal Media?

Nexal Media is a done-for-you social media advertising service. Businesses submit their ad creative and targeting details, pay via Paystack, and the team publishes across their chosen platforms within 24-48 hours.

---

## 📦 Packages

### Starter Pack — ₦15,000/campaign
- Facebook + Instagram
- 1 ad creative (image/video)
- 3-day campaign
- Basic targeting
- Performance report

### Growth Pack — ₦50,000/campaign
- Facebook, Instagram, TikTok, YouTube, X (Twitter), LinkedIn
- Up to 3 ad creatives
- 7-day campaign
- Advanced targeting (demographics, interests, retargeting)
- Weekly performance reports
- A/B testing
- Dedicated account manager

---

## 🌐 Supported Platforms

1. Facebook (Meta Ads)
2. Instagram (Meta Ads)
3. TikTok (TikTok for Business)
4. YouTube (Google Ads)
5. X / Twitter (Twitter Ads)
6. LinkedIn (LinkedIn Ads)

---

## 💳 Payment

- Provider: Paystack (NGN)
- Auto-invoice on submission
- Webhook confirmation
- Supported: Cards, Bank Transfer, USSD

---

## 🗄️ Database Entity

**NexalAdSubmission**
| Field | Type |
|---|---|
| business_name | string |
| contact_email | string |
| contact_phone | string |
| ad_headline | string |
| ad_description | string |
| media_url | string |
| platforms | string (comma-separated) |
| package | string (starter/growth) |
| amount | number |
| currency | string |
| payment_status | string |
| paystack_reference | string |
| publish_status | string |
| admin_notes | string |

---

## 🔭 Roadmap

- [ ] Self-serve ad manager dashboard
- [ ] Real-time campaign analytics
- [ ] Pixel integration (Facebook, TikTok)
- [ ] Automated ad scheduling
- [ ] AI ad copy generator
- [ ] Bulk campaign manager
- [ ] Reseller/agency white-label
- [ ] Google Display Network
- [ ] Influencer marketplace integration
- [ ] WhatsApp ad push notifications

---

## 🏗️ Tech Stack

- Frontend: Server-side rendered HTML (Base44 Deno functions)
- Backend: Base44 serverless functions
- Database: Base44 entity store
- Payments: Paystack API
- Webhook: /functions/harzWebhook (unified Paystack handler)

---

## 📄 License

MIT — Built by Harz Technology Group
