# GitHub Profile Setup Guide

## Step 1 — Create the profile README repository

GitHub profile READMEs require a **public** repository named **exactly your username**:

```
VamshiKrishnaBandari07/VamshiKrishnaBandari07
```

1. Go to https://github.com/new
2. Repository name: `VamshiKrishnaBandari07` (must match username exactly)
3. Public · Add a README · Create repository
4. Replace the default README with the content from this folder

Or push from terminal:

```powershell
cd "c:\Users\VAMSHI KRISHNA\OneDrive\Documents\usa 7\github-profile"
git init -b main
git add README.md
git commit -m "Add professional GitHub profile README"
git remote add origin git@github.com:VamshiKrishnaBandari07/VamshiKrishnaBandari07.git
git push -u origin main
```

---

## Step 2 — Edit GitHub profile settings

Go to: https://github.com/settings/profile

| Field | Recommended value |
|-------|-------------------|
| **Name** | Vamshi Krishna Bandari |
| **Bio** | MSc Artificial Intelligence · Applied ML researcher · Intelligent systems for healthcare & decision support |
| **Company** | University of Roehampton |
| **Location** | London, United Kingdom |
| **Website** | https://www.linkedin.com/in/vamshi-krishna-bandari-623580212 |

### Alternative bios (GitHub limit: 160 characters)

Pick one for **Settings → Profile → Bio**:

1. **Recommended:** `MSc Artificial Intelligence · Applied ML researcher · Intelligent systems for healthcare & decision support` *(97 chars)*

2. `MSc Artificial Intelligence graduate · Explainable AI, predictive modeling & intelligent systems for real-world applications` *(119 chars)*

3. `MSc AI · Researching machine learning and intelligent systems for healthcare, analytics, and responsible deployment` *(112 chars)*

4. **Short:** `MSc Artificial Intelligence · Machine learning · Intelligent systems · Applied research` *(78 chars)*

## Step 3 — Pin your best repositories (6 max)

Go to: https://github.com/VamshiKrishnaBandari07?tab=repositories → **Customize your pins**

Recommended order:

1. **donorlink** — flagship KidneyX project
2. **MSc-CAPSTONE-PROJECT-SOH-RUL-PREDICTION--**
3. **Credit-Risk-Prediction-Agent**
4. **DT-AttNet**

---

## Step 4 — Add descriptions to repos missing them

| Repo | Description |
|------|-------------|
| **donorlink** | Agentic AI platform for living kidney donation — RAG education, multi-agent support, SHAP dropout-risk analytics. KidneyX EMPOWER · Team VK7 |
| **MSc-CAPSTONE-PROJECT-SOH-RUL-PREDICTION--** | MSc capstone: State of Health (SOH) and Remaining Useful Life (RUL) prediction using machine learning |
| **DT-AttNet** | Deep learning architecture with attention mechanisms for [add your specific use case] |

---

## Step 5 — Add topics to donorlink

```
kidneyx healthcare-ai living-donor rag fastapi react typescript
clinical-decision-support explainable-ai agentic-ai
```

---

## Step 6 — Optional polish

- [ ] Add a professional headshot as your GitHub avatar
- [ ] Enable **Private contributions** if you have private repo activity
- [ ] Add a `CONTRIBUTING.md` to donorlink for open-source credibility
- [ ] Link donorlink in your LinkedIn featured section

---

## Note about your existing `profile` repo

The repo named `profile` does **not** display on your GitHub homepage. Only a repository named **`VamshiKrishnaBandari07`** (matching your username) shows as your profile README.
