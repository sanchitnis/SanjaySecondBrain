Here is a structured “detailed transcript” with key concept links back to exact times in the video.



> Video: Dr. Manish Gupta – Inclusive AI – ACM India Summer School 2025 \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

> Base link used below: `https://www.youtube.com/watch?v=pW\_jT8mHXGE`



\*\*\*



\## 1. Opening and Motivation



\- \*\*Introduction and context\*\*  

&#x20; Dr. Manish Gupta thanks the organizers, apologizes for not being there in person, and acknowledges a recent tragedy before starting his talk titled “Inclusive AI.” He explains that inclusive AI means building AI that works for everyone, especially billions who have not yet benefited from AI, aligning with Google DeepMind’s mission to build AI responsibly to benefit humanity. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[0:00–1:00](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=0s)



\- \*\*AI for scientific discovery and AlphaFold\*\*  

&#x20; He highlights that AI’s role in advancing scientific discovery receives less attention than consumer applications, citing the Nobel Prize in Chemistry awarded to Demis Hassabis and John Jumper (Google DeepMind) for AlphaFold as a signal of AI’s scientific impact. He reviews how protein structure prediction went from taking 3–5 years for a single protein to seconds with AlphaFold, and describes AlphaFold’s performance in CASP, release of structures for about 200 million proteins, and widespread global use for drug discovery, enzyme design for degradable plastics, and crop-related applications. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[1:00–4:20](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=60s)



\*\*\*



\## 2. From Deep Learning to Foundation Models



\- \*\*Deep learning breakthroughs post‑2011\*\*  

&#x20; He reviews the 2011–onward breakthroughs where deep learning and artificial neural networks, after a revival, became state of the art for many ML tasks. He describes successes in image classification, speech recognition (replacing cascaded acoustic and language models), and machine translation, emphasizing end‑to‑end training on millions of labeled examples. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[5:20–7:20](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=320s)



\- \*\*Limitations of task‑specific deep models\*\*  

&#x20; Despite their success, these models required large labeled datasets per task and fresh training for every new problem, unlike humans who build on prior knowledge. This motivated a shift from specialized models to \*\*foundation models\*\*. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[7:20–8:10](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=440s)



\- \*\*Transformers and BERT\*\*  

&#x20; He introduces the transformer architecture (“Attention Is All You Need”) as a key breakthrough underlying foundation models. He then describes BERT (2018): trained via self‑supervised learning on public text (Wikipedia, books) by masking 15 percent of tokens and predicting them using transformers, which learn to attend to relevant context like “Obama 1961 Hawaii” to predict “born.” This training gave BERT strong performance on many NLP tasks including sentiment analysis, question answering, and summarization. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[8:10–10:40](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=490s)



\- \*\*PaLM and the “foundation model” idea\*\*  

&#x20; He then discusses PaLM (540B parameters) and an experiment comparing one PaLM model across 58 tasks with the then‑best specialized model for each task. PaLM beat specialized models on most tasks, motivating Stanford’s term “foundation model” because one model gives a solid base for many problems. This led to systems like ChatGPT (OpenAI’s GPT series) and Google’s Gemini. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[10:40–12:00](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=640s)



\*\*\*



\## 3. Gemini Capabilities: Multimodal and Long Context



\- \*\*Multimodal nature of current models\*\*  

&#x20; He notes that although “LLM” suggests text only, modern models like Gemini are \*\*natively multimodal\*\*, handling text, audio, images, and video. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[12:00–12:40](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=720s)



\- \*\*Gemini 1.5 and million‑token context\*\*  

&#x20; Gemini 1.5 (launched around February of the previous year) introduced a long context window: first 1 million tokens, later 2 million. This allows large inputs such as long videos or document sets. He shows an example using a 44‑minute Buster Keaton film (\~600k tokens) uploaded to Google AI Studio; Gemini 1.5 Pro correctly locates the exact time when a piece of paper is removed from a pocket and extracts pawn‑ticket details and the time code (12:01). Another example: given a rough sketch of a scene, Gemini finds the correct time code (15:34) in the film, illustrating multimodal queries with combined text and image. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[12:40–15:30](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=760s)



\- \*\*Gemini 2.0 and agentic behavior (Project Astra / Mariner)\*\*  

&#x20; He explains that about six months earlier, Gemini 2.0 was launched, enabling more \*\*agentic\*\* capabilities. Project Astra is a research prototype of a universal AI assistant that sees and hears the world, uses multimodal memory, and accesses real‑time information to understand the environment, for example describing a sculpture (“My World and Your World” by Eva Rothschild in London) and the themes of the artist’s work, switching languages as needed. Project Mariner aims at agents that can complete multi‑step tasks such as researching an artist, finding a painting, and then shopping for supplies, planning and taking web actions under user control. Gemini 2.0 agents can also help in video games (suggesting attack strategies) and in robotics by understanding 3D spatial environments and assisting in physical settings. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[15:30–18:10](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=930s)



\- \*\*AI tutor demonstration for chemistry\*\*  

&#x20; He then shows a learning‑focused agent demo: a student asks for help with a question on optical isomerism. The agent explains chiral carbons (bonded to four different groups), guides the student through drawing carbon chain structures, identifies a mistake (extra hydrogen), confirms the chiral center, and visualizes two optically active isomers (enantiomers) of a compound. He warns the examples are likely cherry‑picked but illustrate how capable such assistants already are for education. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[18:10–20:40](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=1090s)



\*\*\*



\## 4. Creative AI and Deepfake Mitigation



\- \*\*Creativity and content generation\*\*  

&#x20; He reflects that many expected AI to automate mundane tasks, but significant progress has come in creative domains over the last 5–7 years. Models now help draft emails, write poetry, create high‑quality images, videos, and presentations. He shows images generated by Google’s Imagen‑4 text‑to‑image model and an example of a fully AI‑generated video from a text prompt using a V3 model, noting the increasing presence of such content on social media and the likely future where substantial portions of film production (Hollywood/Bollywood) use AI‑generated footage. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[20:40–23:40](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=1240s)



\- \*\*Watermarking synthetic media (SynthID)\*\*  

&#x20; To guard against deepfakes, he describes SynthID from Google, which embeds a digital watermark in AI‑generated images, videos, and text so systems can detect whether content is synthetic or human‑generated. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[23:40–24:30](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=1420s)



\*\*\*



\## 5. Inclusive AI: Language and Culture



\- \*\*Performance gaps across languages\*\*  

&#x20; He turns to inclusivity and notes a significant capability gap between performance on English and many other widely spoken languages, especially in India. As evidence, he cites \*\*IndicBench\*\*, a benchmark suite (about 100,000 tasks across 29 Indian languages) covering tasks such as machine translation and cross‑lingual QA (question in Hindi, answer content in English, response in Hindi). Models perform much better in English than in Indian languages. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[24:30–26:10](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=1470s)



\- \*\*Multilingual models: MURAL, MuRIL, and “more money” model\*\*  

&#x20; To close these gaps, the DeepMind India team built multilingual models. Earlier, they built MURAL (covering 16 Indian languages). Challenged to cover all 22 scheduled languages, the team lead Partha Talukdar looked at language survey data showing 60 Indian languages with over 1 million speakers and about 125 with more than 100,000 speakers. They set a goal to build a model (the “MoreMuni” / “MoreMany” model, pronounced “more money” in the talk) that understands 125+ Indian languages, aiming to provide access to information in people’s \*\*native language\*\*, including for a laborer’s daughter in Chhattisgarh or a farmer’s son in Assam who may not know English. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[26:10–28:10](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=1570s)



\- \*\*Zero‑corpus languages and dialect diversity\*\*  

&#x20; He notes that at the start of this effort 72 of the targeted \~125 languages were \*\*zero‑corpus\*\*, with no digital data. He also emphasizes that languages vary significantly every few kilometers in India, motivating region‑anchored data collection. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[28:10–28:50](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=1690s)



\- \*\*Vani speech project with IISc and Bhashini\*\*  

&#x20; The proverb about speech variation inspired \*\*Project Vani\*\*, launched with IISc Bangalore, to collect speech data across India in a region‑anchored way. Speakers are shown locally relevant images and asked to describe them in their favorite language, then label the language used. Phase 1 collected about 14,000 hours of audio from 80 districts, covering 59 Indian languages and turning 15 zero‑corpus languages into ones with the first known digital speech data, released via IISc’s Vani site and the Government of India’s Bhashini program. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[28:50–30:45](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=1730s)



\- \*\*Composing models with CAM and PaLM 2 NTL\*\*  

&#x20; Next, he describes the problem of combining a strong Indian‑language model with Gemini’s multimodal strengths. The team’s \*\*CAM\*\* (Cross‑Attention based Model composition) approach, presented at ICLR, composes two independently trained language models using cross‑attention, yielding a fused model that inherits capabilities of both. This can also combine domain‑specific models (e.g., clinical or code) with generalist models like Gemini. Using multilingual models that understand over 1000 languages (PaLM 2 NTL – “Next Thousand Languages”), Google Translate added 110 new languages at once (its largest expansion so far), including seven new Indic languages, bringing Indian language coverage in Translate to 28. He mentions emotional user feedback from communities whose languages were newly supported. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[30:45–33:45](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=1845s)



\- \*\*Cultural grounding, not just translation\*\*  

&#x20; He stresses that inclusive AI must respect culture, not just language. For example, answering a user in Assam should not mean drafting an English response then translating it; instead the answer must be rooted in Assamese cultural context. His team is actively working on cultural grounding. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[33:45–34:35](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=2025s)



\*\*\*



\## 6. Efficient and Elastic Foundation Models



\- \*\*Scaling to billions: efficiency and energy\*\*  

&#x20; He raises the challenge of serving billions of users. Even at millions of users, energy consumption in data centers for generative models is very high, so efficiency is critical if, for example, a billion Indians are to be served without exhausting data‑center power. DeepMind’s efficiency work started from a focus on mobile devices (the primary digital device for hundreds of millions in India) but later turned out to be equally important for servers. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[34:35–36:10](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=2075s)



\- \*\*Matrioska transformers (MatFormer)\*\*  

&#x20; He introduces \*\*Matrioska models / Matrioska transformers (MatFormers)\*\*, inspired by nested Russian dolls. A large model (e.g., 16B parameters, like a Gemini configuration) is trained so that inside it are nested smaller models (8B, 4B, 2B, 1B and intermediate sizes). Empirically, these automatically derived smaller models perform as well as or better than independently trained models of the same size due to knowledge distillation from the larger model. This enables \*\*elasticity of model capacity\*\*: complex queries (e.g., “solve this complex math problem”) go to the largest sub‑model, medium tasks (e.g., “summarize this email”) to mid‑size models, and simple factual queries (e.g., “who is the CEO of Google?”) to the smallest model, saving compute and energy while preserving quality. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[36:10–39:30](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=2170s)



\- \*\*Speed‑up techniques: Tandem Transformer, TreeFormer, HiRe\*\*  

&#x20; He then outlines several system‑level optimizations integrated into Gemini:  

&#x20; - \*\*Autoregressive generation bottleneck and Tandem Transformer\*\*: since responses are generated token by token (autoregressively) and this is sequential, it creates latency. The \*\*Tandem Transformer\*\* uses a smaller model to generate tokens in tandem with the large model, leveraging the large model’s key–value cache, to speed up generation. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; - \*\*Attention complexity and TreeFormer\*\*: standard attention is \\(O(n^2)\\) in the number of tokens. \*\*TreeFormer\*\* clusters tokens and uses a decision‑tree‑like mechanism to find relevant clusters, reducing complexity towards \\(O(n \\log n)\\). \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; - \*\*Softmax acceleration (HiRe‑like approach)\*\*: during softmax over the vocabulary, instead of exhaustively considering all entries, approximate methods select the top‑K candidates cheaply and compute softmax only over them, speeding up inference. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)



&#x20; These contribute to Gemini Flash, which he describes as the highest‑performing model per rupee and per watt and more cost‑efficient than DeepSeek R1, arguing that some claims about DeepSeek’s efficiency improvements are exaggerated even though its openness and performance are commendable. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[39:30–45:20](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=2370s)



\*\*\*



\## 7. Applications in Public Health and Agriculture



\- \*\*Overview of application focus\*\*  

&#x20; Having covered foundational technologies for inclusivity and efficiency, he moves to applications in areas like public health and agriculture, which also drive new capabilities. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[45:20–45:50](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=2720s)



\- \*\*Public health: ARMMAN and Saheli (restless multi‑armed bandits)\*\*  

&#x20; In public health, he describes work led by Prof. Milind Tambe with the NGO \*\*ARMMAN\*\*, which runs a mobile voice messaging program for maternal and child health. Pregnant women receive two voice messages per week with guidance (e.g., taking iron tablets to reduce anemia). Listening correlates with better health outcomes, but many women drop out. ARMMAN asked for help predicting which women are at high risk of dropping out and are likely to benefit from outreach so volunteers can prioritize them. The team framed this as a \*\*restless multi‑armed bandit\*\* problem, where “arms” correspond to women to be contacted. Their AI system, \*\*Saheli\*\*, was deployed and evaluated through randomized controlled trials, improving engagement among the poorest listeners (bottom 25 percent) by about 30 percent in listening time, with additional studies showing improved awareness and health actions. They also developed \*\*decision‑focused learning\*\* methods that optimize directly for which women to contact rather than separating risk prediction and benefit estimation. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[45:50–50:00](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=2750s)



\- \*\*Agriculture: satellite‑based agri‑stack\*\*  

&#x20; He briefly summarizes work (covered in more detail in another talk by a colleague) on a model that uses satellite imagery to automatically identify farm boundaries and crop types. This is intended as a foundational layer for a \*\*digital agricultural stack\*\*, enabling services such as more accurate loans and insurance products for farmers. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[50:00–51:10](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3000s)



\*\*\*



\## 8. Remaining Challenges: Factuality, Safety, Bias, AGI



\- \*\*Technical and ethical challenges\*\*  

&#x20; He emphasizes that despite impressive progress there are major open challenges:  

&#x20; - \*\*Efficiency\*\*: further reducing compute and energy for large‑scale deployment. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; - \*\*Factuality and hallucinations\*\*: ensuring models stick to facts and avoid generating incorrect information. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; - \*\*Robustness and safety\*\*: particularly in health, where wrong predictions can harm individuals. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; - \*\*Bias and fairness\*\*: large models inherit biases from data. Work in the West has focused on gender and race; his team has documented biases relevant to India such as nationality, caste, and religion. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; - \*\*Planning and reasoning\*\*: as we move toward artificial general intelligence, robust planning and reasoning remain difficult. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)



&#x20; Time: \[51:10–52:55](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3070s)



\- \*\*Closing remarks and call to students\*\*  

&#x20; He concludes that AI already affects every industry and aspect of how the world operates, driven by foundation models trained via self‑supervised and generative methods. He calls this an extraordinary time to be in computing and AI: with AI as a powerful enabler, students can tackle any major problem they care about and build solutions that benefit billions. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[52:55–54:40](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3175s)



\*\*\*



\## 9. Selected Q\&A Highlights



\- \*\*Q1: Non‑language DeepMind projects (science, energy, materials)\*\*  

&#x20; A student asks about major DeepMind projects beyond language models and Google I/O demos. Gupta mentions a dedicated unit focused on \*\*AI for scientific discovery\*\* beyond AlphaFold, such as AlphaFold‑related design of proteins, collaborations using diffusion models, work in clean energy and material science, and especially \*\*controlled nuclear fusion\*\*. He explains that current lab fusion requires more energy input than output but DeepMind collaborates with a fusion startup using reinforcement learning for plasma control, aiming to reach break‑even within 2–3 years, which would unlock clean energy with no radioactive waste. He also mentions AI for designing new materials. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[55:15–56:30](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3315s)



\- \*\*Q2: Data work, annotation, and RLHF pipeline\*\*  

&#x20; Another question concerns why AI systems often fail in Indian settings and the large but invisible work of data annotation and cleaning. He outlines a typical industrial‑scale pipeline: massive self‑supervised pre‑training, followed by supervised fine‑tuning on high‑quality labeled data from annotation firms, and then \*\*RLHF\*\* (reinforcement learning from human feedback) where humans rank model outputs for preference. He notes that modeling work gets the glamour while data work is undervalued, referencing an award‑winning CHI paper co‑authored by his colleagues highlighting this imbalance, and mentions organizations like \*\*Karya\*\* that pay annotators significantly above minimum legal rates to compensate them more fairly. He also reiterates that performance gaps are especially large for Indian languages and voice queries. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[58:00–1:02:30](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3480s)



\- \*\*Q3: Keeping up with overwhelming research volume\*\*  

&#x20; A question raises concerns that even Nobel‑level scientists struggle to keep up with the pace of publications and that students feel “FOMO” because there is too much to explore. He suggests using AI tools themselves to cope: assistants with “deep research” modes, Google’s \*\*NotebookLM\*\* (for ingesting papers and asking questions, including via an AI‑generated podcast interface), and experimental tools from DeepMind that read literature and help scientists generate hypotheses. He points out that medicine has long faced this challenge, and AI can help clinicians and researchers stay current. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[1:02:30–1:07:10](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3750s)



\- \*\*Q4: Data scarcity vs processing capability for low‑resource languages\*\*  

&#x20; Another question asks whether low‑resource languages lack data or processing capability. He answers that for many languages the data simply does not exist or is tiny compared to dominant languages, so their signal is drowned out in model parameters. He then describes using \*\*in‑context learning\*\* as a promising method: for a language spoken by fewer than 200 people worldwide with almost no pre‑training representation, they feed a 1‑million‑token context that includes a grammar book and bilingual dictionaries (language–English and English–language) plus queries. Under such set‑up, the model can reach performance comparable to a human learner for that language, showing how transformers can learn new languages from context alone. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[1:07:10–1:09:00](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=4030s)



\- \*\*Q5: New architectures beyond transformers\*\*  

&#x20; The final question asks whether Google is working on architectures beyond transformers. He replies that this is an active research goal, but transformer‑based architectures remain dominant even 7–8 years after “Attention Is All You Need,” with only incremental tweaks so far. He confirms that teams are exploring new architectures and training methods (including diffusion‑based ideas), but transformers are still the main workhorse today. \[youtube](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=3351s)

&#x20; Time: \[1:09:00–1:17:10](https://www.youtube.com/watch?v=pW\_jT8mHXGE\&t=4140s)





