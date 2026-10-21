# 📊 Project Details

Detailed information, features, and links for all my projects.

---

## WasteRefine (Academic Thesis)

An academic research study on deep learning-based semantic segmentation for automated recyclable waste sorting in Material Recovery Facilities (MRFs).

### 🔗 Links
- **GitHub Repository:** [ahnaf-iqbal/WasteRefine](https://github.com/ahnaf-iqbal/WasteRefine)
- **Dataset:** [WasteRefine on Roboflow Universe](https://universe.roboflow.com/talha-ljqb5/wasterefine)
- **Executive Summary:** [RESEARCH_SUMMARY.md](https://github.com/ahnaf-iqbal/WasteRefine/blob/main/RESEARCH_SUMMARY.md)

### 🚀 Key Highlights & Contributions
- **Novel Architecture:** Designed WasteRefine, an object-aware segmentation framework combining self-supervised DINOv2 Vision Transformers with a multi-scale decoder, Pyramid Pooling (PPM), Squeeze-and-Excitation (SE) attention, and boundary edge supervision.
- **Novel Dataset:** Collected and annotated the WasteRefine Dataset—the first dedicated municipal waste semantic segmentation benchmark from Bangladesh (2,213 images across 4 recyclable material categories).
- **Benchmark Evaluations:** Tested across WasteRefine, ZeroWaste-F, and SpectralWaste benchmarks, outperforming existing published baselines on cluttered and imbalanced environments.
- **Parameter Efficiency:** Demonstrated that an optimized lightweight model variant achieves strong segmentation accuracy with fewer parameters.

### 🛠️ Tech Stack & Methods
- **Domain:** Computer Vision, Semantic Segmentation, Environmental Sustainability
- **Frameworks:** PyTorch, Torchvision, Transformers (Hugging Face)
- **Backbone & Decoder:** DINOv2 (ViT-B & ViT-S), Dense Prediction Transformer (DPT), PPM, SE Attention

---

## Stockwatch Beta

An advanced, full-stack stock tracking and market analysis web application that allows users to monitor real-time stock prices, manage personalized watchlists, and receive AI-driven news summaries.

### 🔗 Links
- **Live Demo:** [https://stockwatch-olive.vercel.app/sign-in](https://stockwatch-olive.vercel.app/sign-in)
- **GitHub Repository:** [ahnaf-iqbal/stockwatch_beta](https://github.com/ahnaf-iqbal/stockwatch_beta)

### 🚀 Key Features
- **Real-Time Market Data:** Interactive price charts and financial news updates powered by the Finnhub API.
- **AI-Powered Analytics:** Integrates OpenAI API for automated news digests, welcome messages, and personalized watchlist analysis.
- **Intelligent Notification System:** Real-time in-app alerts and scheduled email notifications (via Nodemailer SMTP) with user-configurable preferences (e.g., email toggles, quiet hours).
- **Secure Authentication:** User signup, login, and session management powered by Better Auth.
- **Persistent Storage:** MongoDB database integration for managing user watchlists, settings, and notification history.

### 🛠️ Tech Stack
- **Framework:** Next.js (App Router), TypeScript
- **Database:** MongoDB
- **Styling:** Tailwind CSS, Shadcn UI
- **Authentication:** Better Auth
- **APIs & Tools:** OpenAI (AI features), Finnhub (Market data), Nodemailer (SMTP emails)
