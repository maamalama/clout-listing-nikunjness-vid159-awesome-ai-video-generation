# Awesome AI Video Generation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI video generation tools, models, APIs, datasets, and learning resources.

AI video generation moved from research demos to production workflows between 2024 and 2026. The space now spans hosted creative suites, foundation models with native audio, open-weight diffusion transformers, and a growing layer of inference APIs and avatar tools. This list tracks what is currently active and worth evaluating.

## Contents

- [Hosted Tools](#hosted-tools)
  - [Text-to-Video](#text-to-video)
  - [Image-to-Video](#image-to-video)
  - [Multimodal](#multimodal)
  - [Video-to-Video / Editing](#video-to-video--editing)
  - [AI Avatars & Lip Sync](#ai-avatars--lip-sync)
- [Foundation Models](#foundation-models)
- [APIs & Aggregators](#apis--aggregators)
- [Open-Source Models](#open-source-models)
- [Datasets](#datasets)
- [Tutorials](#tutorials)
- [Newsletters & Communities](#newsletters--communities)
- [Related Lists](#related-lists)
- [Contributing](#contributing)
- [License](#license)

## Hosted Tools

### Text-to-Video

- [Runway](https://runwayml.com/) — Gen-4 text and image to video with a professional creative suite, Aleph in-context editing, and Act-Two performance capture.
- [Pika](https://pika.art/) — Text-to-video with Scene Ingredients, Pikaframes keyframe transitions, and Pikaswaps object replacement.
- [Kling AI](https://klingai.com/) — Long-duration text and image to video model from Kuaishou, with director-style camera controls and multi-shot prompts.
- [Hailuo AI](https://hailuoai.video/) — MiniMax video model with Hailuo 02 native 1080p output and a generous free tier.
- [Luma Dream Machine](https://lumalabs.ai/dream-machine) — Text and image to video focused on physics-respecting motion and high-fidelity output.
- [Google Flow](https://labs.google/flow/) — Google DeepMind's filmmaking interface around the Veo model family with scene extension and 4K upscaling.
- [Higgsfield AI](https://higgsfield.ai/) — Cinematic video studio that aggregates Sora 2, Veo, Kling, Wan, and Seedance with 70+ camera presets.
- [Haiper](https://www.haiper.ai/) — Text-to-video model with motion control and image conditioning.
- [Akool](https://www.akool.com/) — Text-to-video plus face swap, talking avatar, and streaming avatar for marketing teams.
- [Adobe Firefly Video](https://firefly.adobe.com/generate/video) — Browser-based text-to-video integrated with Adobe Creative Cloud, with multi-track Firefly Video Editor and 4K HDR export.
- [Dreamina (CapCut)](https://dreamina.capcut.com/) — ByteDance's creator-focused video generator inside CapCut, currently powered by Seedance 2.0.
- [VEED](https://www.veed.io/) — Browser video editor with AI generation, captions, eye-contact correction, and dub tooling.
- [Kapwing](https://www.kapwing.com/) — Online editor with AI script-to-video, auto-captioning, and template-based generation.
- [InVideo AI](https://invideo.io/) — Prompt-to-video for marketing content with stock library and brand kit.

### Image-to-Video

- [Stable Video Diffusion](https://stability.ai/stable-video) — Stability AI's image-to-video model with hosted API access.
- [Runway Image-to-Video](https://runwayml.com/) — Gen-4 image-to-video at up to 4K with motion brush and camera path controls.
- [Kling Image-to-Video](https://klingai.com/) — Image-to-video mode with strong motion adherence and the most generous free credits among premium models.
- [Hailuo 02](https://hailuoai.video/) — Image-to-video at native 1080p with strong physics following.
- [Pika Frames](https://pika.art/) — Generates a 1-10 second transition video between two or more reference frames.
- [Luma Dream Machine](https://lumalabs.ai/dream-machine) — Image-to-video with realistic motion physics.
- [Genmo](https://www.genmo.ai/) — Hosted access to Mochi-family models with image-to-video workflow.
- [Topview AI](https://www.topview.ai/) — Image-to-video with Product Avatar that physically demonstrates the uploaded product.

### Multimodal

Tools that accept combinations of text, reference images, reference video, and audio in a single workflow.

- [Clout](https://tryclout.ai/) — Browser-based AI character creation, image and video generation, and faceless content workflows.
- [Wan 2.6 (Alibaba)](https://www.alibabacloud.com/help/en/model-studio/use-video-generation) — Multi-shot video generation with reference video, voice cloning, and 15-second native audio output.
- [Seedance 2.0 (ByteDance)](https://seed.bytedance.com/en/seedance2_0) — Unified text + image generation with synchronized audio in a single inference pass; restricted to non-US regions as of April 2026.
- [Veo 3.1 (Google)](https://deepmind.google/models/veo/) — Native synced audio, scene extension beyond 60 seconds, and reference-image conditioning via Gemini API.
- [Seedance 2 Cloud](https://seedance2.cloud/) — Hosted API frontend for the Seedance 2 family with reference-image and reference-video conditioning.
- [SkyReels V3](https://github.com/SkyworkAI/SkyReels-V3) — Open multimodal model supporting reference-image, audio-conditioned, and video-to-video generation.
- [Higgsfield Cinema](https://higgsfield.ai/ai-video) — Multi-model studio combining text, reference images, and camera presets across Sora, Veo, Kling, Seedance, and Wan.

### Video-to-Video / Editing

- [Runway Aleph](https://runwayml.com/research/introducing-runway-aleph) — In-context video editor that adds, removes, or replaces objects, changes lighting, and generates new camera angles from existing footage.
- [Pikaswaps & Pikadditions](https://pika.art/) — Object replacement and insertion into existing video while preserving lighting and motion.
- [Topaz Video AI](https://www.topazlabs.com/topaz-video) — Upscaling, frame interpolation up to 120fps, and HDR enhancement; the Astra model is tuned for AI-generated footage temporal consistency.
- [Descript](https://www.descript.com/) — Edit video by editing the transcript, with AI eye contact, studio sound, and overdub.
- [Fluxlabs](https://www.fluxlabs.ai/) — Generative video editing and stylization workflows.

### AI Avatars & Lip Sync

- [HeyGen](https://www.heygen.com/) — AI avatar video with 175+ languages, Avatar IV motion-capture realism, and credit-based pricing.
- [Synthesia](https://www.synthesia.io/) — Enterprise AI avatars with SOC 2 Type II compliance, designed for training and corporate communication.
- [Tavus](https://www.tavus.io/) — Hyper-personalized avatar video and conversational video API for sales and product workflows.
- [D-ID](https://www.d-id.com/) — Real-time streaming talking avatars and conversational agents.
- [Hedra](https://www.hedra.com/) — Image-plus-audio-to-video with Character 3 model focused on facial realism.
- [Sync.so](https://sync.so/) — Lip-sync API and tooling that targets natural mouth movement on existing footage.
- [Vozo](https://www.vozo.ai/) — Multilingual lip sync supporting 110+ languages with multi-speaker scenarios.

## Foundation Models

Models that ship as research artifacts or first-party products, generally accessed via web app or API rather than self-hosted.

- [Sora 2 (OpenAI)](https://openai.com/sora/) — Text-to-video model with strong physical-world simulation; the Sora 1 web app was sunset April 2026, Sora 2 remains accessible until the announced API shutdown.
- [Veo 3.1 (Google DeepMind)](https://deepmind.google/models/veo/) — Foundation video model with native audio generation, available through Gemini API and Vertex AI.
- [Veo 3.1 Lite (Google)](https://blog.google/innovation-and-ai/technology/ai/veo-3-1-lite/) — Cost-optimized variant exposed through the Gemini API.
- [Kling 3 (Kuaishou)](https://klingai.com/) — Multi-shot video model with director physics and reference video conditioning.
- [Hailuo 02 (MiniMax)](https://www.minimax.io/) — Native 1080p video model using Noise-aware Compute Redistribution architecture.
- [Seedance 2.0 (ByteDance)](https://seed.bytedance.com/en/seedance2_0) — Unified video + audio model with multi-subject and reference-image support.
- [Wan 2.6 (Alibaba)](https://github.com/Wan-Video) — 14B-parameter MoE video model trained on 1.5B videos and 10B images; supports multi-shot storytelling.
- [Runway Gen-4](https://runwayml.com/research/) — Runway's flagship video model and the basis for Aleph in-context editing.

## APIs & Aggregators

- [Replicate](https://replicate.com/) — Run open-source video models including Mochi, LTX-Video, Wan, HunyuanVideo, Gen-4 Aleph through a unified API.
- [fal.ai](https://fal.ai/) — Low-latency hosted endpoints for video models including Seedance 2.0, Kling, Hailuo, and Wan.
- [WaveSpeedAI](https://wavespeed.ai/) — Aggregator API across Sora, Kling, Veo, Seedance, Hailuo, Wan, and others.
- [KIE.ai](https://kie.ai/) — Aggregator API exposing Sora, Kling, Runway, Veo, and Seedance under a unified key.
- [AI/ML API](https://aimlapi.com/) — Multi-provider API with OpenAI-compatible endpoints covering Hailuo, Kling, Veo, Runway, and others.
- [Hugging Face Inference Providers](https://huggingface.co/inference-api) — Hosted inference for open video models.
- [NVIDIA NIM](https://build.nvidia.com/stabilityai/stable-video-diffusion) — Containerized inference microservices including Stable Video Diffusion.
- [Vercel AI Gateway](https://vercel.com/ai-gateway) — Unified gateway for routing and observability across model providers.
- [Google Vertex AI](https://cloud.google.com/blog/products/ai-machine-learning/announcing-veo-3-imagen-4-and-lyria-2-on-vertex-ai) — Enterprise endpoint for Veo 3, Imagen 4, and Lyria 2.

## Open-Source Models

Models with public weights, code, or both. License terms vary, check before commercial use.

- [Wan 2.1 (Alibaba)](https://github.com/Wan-Video/Wan2.1) — 1.3B and 14B variants with 8GB VRAM minimum on the smaller model.
- [Wan 2.2 (Alibaba)](https://github.com/Wan-Video/Wan2.2) — Mixture-of-Experts upgrade with separate high-noise and low-noise experts.
- [HunyuanVideo (Tencent)](https://github.com/Tencent-Hunyuan/HunyuanVideo) — 13B-parameter open foundation model with dual-stream-to-single-stream transformer.
- [HunyuanVideo-I2V (Tencent)](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V) — Image-to-video extension of HunyuanVideo.
- [CogVideoX (THUDM)](https://github.com/THUDM/CogVideo) — Tsinghua's open video model, integrated with Hugging Face Diffusers.
- [Open-Sora (HPC AI)](https://github.com/hpcaitech/Open-Sora) — 11B-parameter open reproduction effort with public training pipeline.
- [Open-Sora-Plan (PKU)](https://github.com/PKU-YuanGroup/Open-Sora-Plan) — Independent open Sora-style training and inference codebase.
- [Mochi 1 (Genmo)](https://github.com/genmoai/mochi) — 10B-parameter Apache 2.0 model with Asymmetric Diffusion Transformer.
- [LTX-Video (Lightricks)](https://github.com/Lightricks/LTX-Video) — DiT-based model that generates 30fps video at 1216x704 faster than real time on capable hardware.
- [Stable Video Diffusion (Stability AI)](https://github.com/Stability-AI/generative-models) — Image-to-video diffusion model in the Stability generative-models repo.
- [SkyReels V2 (Skywork)](https://github.com/SkyworkAI/SkyReels-V2) — Open text-to-video and image-to-video with Diffusion Forcing for unlimited-length output.
- [SkyReels V3 (Skywork)](https://github.com/SkyworkAI/SkyReels-V3) — Multimodal in-context model supporting reference, audio, and video-to-video.
- [Step-Video-T2V (StepFun)](https://github.com/stepfun-ai/Step-Video-T2V) — Open text-to-video diffusion model from StepFun.
- [VideoCrafter (Tencent ARC)](https://github.com/AILab-CVC/VideoCrafter) — Apache-2.0 text-to-video and image-to-video models.
- [Allegro (Rhymes AI)](https://github.com/rhymes-ai/Allegro) — Apache-2.0 text-to-video model that runs on 12-24GB VRAM.
- [DynamiCrafter](https://github.com/Doubiiu/DynamiCrafter) — Image-to-video model that animates open-domain still images.
- [I2VGen-XL (Alibaba)](https://github.com/ali-vilab/i2vgen-xl) — Cascaded image-to-video model from DAMO Academy.
- [Latte (Vchitect)](https://github.com/Vchitect/Latte) — Latent diffusion transformer for video.
- [SEINE (Vchitect)](https://github.com/Vchitect/SEINE) — Short-to-long video diffusion with scene transitions.

## Datasets

- [Panda-70M](https://snap-research.github.io/Panda-70M/) — 70M high-resolution video-text pairs with semantic coherence captions.
- [InternVid (OpenGVLab)](https://github.com/OpenGVLab/InternVideo) — 234M video clips with LLM-generated descriptions, totaling 4.1B caption words.
- [WebVid-10M](https://github.com/m-bain/webvid) — 10.7M text-video pairs, 52K hours; original landing page is offline but the GitHub mirror remains active.
- [OpenVid-1M](https://github.com/NJU-PCALab/OpenVid-1M) — 1M+ in-the-wild clips at 512x512+ resolution with detailed captions, ICLR 2025.
- [HD-VILA-100M](https://github.com/microsoft/XPretrain) — 100M high-resolution video-language pairs from Microsoft.
- [LVD-2M](https://arxiv.org/abs/2410.10816) — Long-take video dataset with temporally dense captions.

## Tutorials

- [Diffusion Models for Video Generation (Lil'Log)](https://lilianweng.github.io/posts/2024-04-12-diffusion-video/) — Lilian Weng's tutorial covering U-Net and transformer-based video diffusion architectures.
- [State of open video generation models in Diffusers](https://huggingface.co/blog/video_gen) — Hugging Face survey of open video models and how to run them with the Diffusers library.
- [Creating with Gen-4 Video](https://help.runwayml.com/hc/en-us/articles/37327109429011-Creating-with-Gen-4-Video) — Runway's official documentation for Gen-4 prompting and controls.
- [Creating with Aleph](https://help.runwayml.com/hc/en-us/articles/43176400374419-Creating-with-Aleph) — Runway documentation for in-context video editing with Aleph.
- [Veo on Vertex AI](https://cloud.google.com/blog/products/ai-machine-learning/announcing-veo-3-imagen-4-and-lyria-2-on-vertex-ai) — Google Cloud guide to running Veo 3 in production.
- [Hugging Face Papers](https://huggingface.co/papers) — Trending video generation papers with code links.

## Newsletters & Communities

- [The Batch (DeepLearning.AI)](https://www.deeplearning.ai/the-batch/) — Andrew Ng's weekly research and industry roundup.
- [Import AI](https://importai.substack.com/) — Jack Clark's weekly survey of AI research and policy.
- [Latent Space](https://www.latent.space/) — Engineering-focused AI newsletter and podcast covering model releases and infrastructure.
- [Ben's Bites](https://www.bensbites.com/) — Daily AI product and tooling news for builders.
- [The Rundown AI](https://www.therundown.ai/) — Daily AI news with consumer-tool coverage.
- [Lenny's Newsletter](https://www.lennysnewsletter.com/) — Product and growth newsletter that frequently covers AI tooling.
- [The Algorithmic Bridge](https://thealgorithmicbridge.substack.com/) — Independent AI analysis with model deep dives.
- [AI Breakdown](https://aibreakdown.com/) — Daily AI podcast and newsletter focused on industry shifts.
- [AI Video Prompt Lab](https://aivideoprompts.substack.com/) — Weekly newsletter on permission-based real-face AI video workflows across Seedance 2.0, Runway, Pika, and Kling.

## Related Lists

- [Awesome-Video-Diffusion (showlab)](https://github.com/showlab/Awesome-Video-Diffusion) — Research-focused list of diffusion models for video generation and editing.
- [Awesome-Video-Generation (matthewvowels1)](https://github.com/matthewvowels1/Awesome-Video-Generation) — 250+ papers on video generation and representation learning.
- [Awesome-Text-to-Video-Generation (soraw-ai)](https://github.com/soraw-ai/Awesome-Text-to-Video-Generation) — Companion list to the "From Sora What We Can See" survey.
- [awesome-video-generation (backblaze-labs)](https://github.com/backblaze-labs/awesome-video-generation) — APIs, SDKs, and production tooling for developers.
- [awesome-ai-video-prompts (geekjourneyx)](https://github.com/geekjourneyx/awesome-ai-video-prompts) — Prompt templates and cinematic techniques for Veo, Sora, Kling, Pika, Runway.
- [awesome-generative-ai (steven2358)](https://github.com/steven2358/awesome-generative-ai) — Broader generative AI ecosystem list.
- [Awesome-Diffusion-Models (diff-usion)](https://github.com/diff-usion/Awesome-Diffusion-Models) — General diffusion model resources spanning images, video, and audio.
- [Awesome-AIGC-Tutorials](https://github.com/luban-agi/Awesome-AIGC-Tutorials) — Tutorials and survey papers across AIGC, including video.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for the entry format and quality bar before opening a pull request. Entries must link to active projects, follow the `- [Name](URL) — One-sentence technical description.` format, and avoid superlatives ("best", "amazing", "cool").

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the maintainers have waived all copyright and related or neighboring rights to this work.
