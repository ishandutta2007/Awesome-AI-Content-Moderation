# Awesome-AI-Content-Moderation

# Top AI Content Moderation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Toxicity Detection, NSFW Filtering, Hate Speech Classification, Multimodal Safety & Automated Trust & Safety*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Content Moderation**. These systems score or block text, images, audio, and video for toxicity, hate, sexual content, violence, spam, and policy violations—helping platforms keep communities safe at scale.

**Examples** include Hive, ActiveFence, Spectrum Labs, WebPurify, Sightengine, OpenAI Moderation, Azure AI Content Safety, Google Cloud Content Safety, Amazon Rekognition Moderation, and Checkstep (the category leaders).

**Open-source emphasis**: Strong open models exist for toxicity and NSFW detection. **Detoxify**, **toxic-bert**, **Falconsai NSFW**, **rembg-style classifiers**, and self-hosted APIs like **LocalMod** enable private moderation pipelines. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Hive](https://thehive.ai/)**  
  Multimodal AI moderation platform for text, image, video, and audio—widely used for trust & safety at scale.

- **[ActiveFence, Spectrum Labs, Checkstep](https://www.activefence.com/)**  
  Trust & safety platforms focused on harmful content detection, policy enforcement, and online risk across modalities.

- **[Sightengine, WebPurify](https://sightengine.com/)**  
  Image and text moderation APIs for NSFW, unwanted content, and user-generated media filtering.

- **[OpenAI Moderation API](https://platform.openai.com/docs/guides/moderation)**  
  Free moderation endpoint classifying text (and related inputs) for hate, self-harm, sexual, and violence categories.

- **[Azure AI Content Safety, Google Cloud Content Safety, Amazon Rekognition Moderation](https://azure.microsoft.com/products/ai-services/ai-content-safety)**  
  Cloud provider moderation APIs for text and vision—toxicity, adult content, violence, and custom policies.

- **[Other commercial content moderation platforms](https://thehive.ai/)**  
  Additional solutions for live streaming, gaming, and marketplace trust & safety.

## Open-Source GitHub Projects

- **[Detoxify](https://github.com/unitaryai/detoxify)**  
  Popular open-source library for toxic comment classification—multi-label scores for toxicity, severe toxicity, obscenity, threat, insult, and identity attack.

- **[unitary/toxic-bert & hate-speech models](https://huggingface.co/unitary)**  
  Open Transformers models fine-tuned for toxicity and hate speech; widely used as building blocks in custom moderators.

- **[Falconsai NSFW image detection](https://huggingface.co/Falconsai/nsfw_image_detection)**  
  Widely downloaded open vision model for NSFW image classification; powering many self-hosted image moderation APIs.

- **[moderators (viddexa)](https://github.com/viddexa/moderators)**  
  One-package open API/CLI to run NSFW and other moderation models from the Hub with normalized JSON output.

- **[LocalMod](https://github.com/KOKOSde/localmod)**  
  Self-hosted content moderation API for text and image—toxicity ensemble, NSFW, spam, PII, and prompt-injection checks; data stays on your server.

- **[OpenGuard AI & multimodal frameworks](https://github.com/wispas/openguardai)**  
  Open multimodal content detection frameworks aimed at toxic/unsafe text (and roadmap for image/audio/video).

- **[Safe Content AI & NSFW API wrappers](https://github.com/steelcityamir/safe-content-ai)**  
  Open FastAPI services wrapping NSFW image models for easy self-hosted moderation endpoints.

- **[LLM Guard & safety scanners](https://github.com/protectai/llm-guard)**  
  Open scanners for toxicity, NSFW, PII, and related signals on LLM inputs/outputs—usable as a moderation layer.

### Additional Strong Open-Source Options

- **Text toxicity**: Detoxify and toxic-bert ensembles for comments and chat.
- **Image NSFW**: Falconsai and similar ViT models via moderators or custom APIs.
- **Self-hosted API**: LocalMod or Safe Content AI for private, offline-capable moderation.
- **LLM applications**: LLM Guard for prompt/response filtering in agent and chat products.
- **Composable stacks**: Open text + image classifiers → policy engine → human review queue.
- Commercial platforms still lead in multimodal coverage, adversarial robustness, and 24/7 policy ops.

**Frameworks for building custom systems**:  
**Detoxify** + **toxic-bert** for text; **Falconsai NSFW** (or moderators package) for images; **LocalMod** or custom FastAPI for a unified self-hosted API.  
Add **LLM Guard** when moderating generative AI traffic.  
Commercial APIs (Hive, OpenAI Moderation, Azure/Google/AWS, Sightengine, ActiveFence, etc.) provide scale, multilingual coverage, and managed updates.  
Many platforms combine open models for cost-sensitive or private traffic with commercial APIs for high-risk or multimodal needs. Fully open stacks are viable for text-heavy and basic image moderation with careful tuning and human escalation.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Automated moderation is imperfect—false positives and false negatives are expected. Always provide human appeal paths and review high-impact decisions. Cultural and linguistic context matters; models trained primarily on English may underperform elsewhere.
- Open-source models offer privacy and control but require you to maintain accuracy, bias testing, and policy alignment. Commercial platforms shift model updates and support to the vendor. Neither replaces clear community guidelines and trained moderators.

---

**Made for trust & safety teams, platform engineers, and builders of safer online communities.**  
Let's expand open content moderation while recognizing the scale and multimodal depth that leading commercial platforms deliver.
