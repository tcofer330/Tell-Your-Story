# 📋 Project Checklist – *Photo of the Week*

## Phase 1 – Foundations
- [x] **Step 1:** AWS account hardening & budgets  
  - Create IAM admin user  
  - Enable MFA on root & IAM  
  - Set up AWS Budgets & alerts  

- [x] **Step 2:** Project repo + Git/GitHub setup  
  - Create GitHub account & repo  
  - Add `README.md`, `LICENSE`, `.gitignore`  
  - Clone repo locally & sync with GitHub  
  - Install VS Code + `code` command  

- [ ] **Step 3:** Core infra scaffolding (SST hello-world app)  
  - Install SST in project folder  
  - Deploy hello-world Lambda + API Gateway  
  - Confirm endpoint works  

---

## Phase 2 – Photo Upload & Processing (MVP)
- [ ] Add S3 upload flow (pre-signed URLs)  
- [ ] Add Lambda to resize images & make thumbnails  
- [ ] Store photo metadata in DynamoDB  

---

## Phase 3 – Voting & Leaderboards
- [ ] Implement voting API (1 vote/user/week)  
- [ ] Add anti-abuse (rate limiting)  
- [ ] Weekly & monthly leaderboards  

---

## Phase 4 – Stories & Auto-Translate
- [ ] Add user preferred language (Cognito attribute)  
- [ ] Add story submission (text + optional audio)  
- [ ] Detect language (Comprehend)  
- [ ] Translate on read (Translate + DynamoDB cache)  
- [ ] Add optional Polly (text-to-speech)  

---

## Phase 5 – Rewards & Payouts
- [ ] Automate monthly winner selection (EventBridge + Lambda)  
- [ ] Add Stripe/PayPal payout integration  
- [ ] Add fraud/suspicion checks  

---

## Phase 6 – Moderation & Safety
- [ ] Profanity/harassment filters  
- [ ] Remove EXIF metadata (GPS, etc.)  
- [ ] Add content flagging system  
- [ ] Build admin dashboard for review  

---

## Phase 7 – Observability & Ops
- [ ] CloudWatch dashboards (usage, costs, errors)  
- [ ] Add alarms (errors, DynamoDB throttles, API spikes)  
- [ ] Add X-Ray tracing  

---

✅ Current Status: **Paused at Phase 1 – Step 3**
