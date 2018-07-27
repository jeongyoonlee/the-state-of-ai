# The State of AI

This repository compiles latest discussions and resources around the state of artificial intelligence (AI). Any contributions are welcome.

## GENERAL

### Keynotes

#### [The State of AI](https://www.youtube.com/watch?v=NKpuX_yzdYs) by Andrew Ng at [EmTech](https://events.technologyreview.com/emtech/18/) (2017)
* Supervised learning: A (an image) --> B (cat or dog)
* Reinforcement learning: Even greater hunger for data and computation
* Data asset is more important than algorithms.
* Virtuous cycle of getting data: data --> product --> users --> more data
* Tech company with NN != AI company, such as shopping mall with a website != internet compnay
  * Strategic data acquisition
  * Unified data warehouse - multi-year exercise
  * New job description for PMs
* To incorporate AI into a company, a centralized AI team that provides AI resources to different business units across the company is recommended.
  * More consistent management of AI talents
  * Common standards and company-wide platform

#### [The Power and Limits of AI: Present and Future](https://www.youtube.com/watch?v=uEZ-V5CXNI8&t=1258s) by Yann LeCun at Abu Dhabi Ideas Weekend (2018)
* AI: Started in 50s. Had success with expert systems in 80s. Revived with the emergence of deep learning
* Deep learning is an internal structure of machine in machine learning
* Authentic human experience > material goods
* AI is a general purpose technology (GPT)
  * GPT: steam engin, electricity, computer, etc.
  * Technology deployment is limited by how fast workers can train for it. Needs investment on education.

#### [The Frontiers of Machine Learning and AI](https://www.oreilly.com/ideas/the-frontiers-of-machine-learning-and-ai) by Zoubin Ghahramani at Oreilly AI Conference in NY (2018)

### Reports

#### [State of AI 2018](https://www.youtube.com/watch?time_continue=11&v=ja6TsWNDXVg) by CB Insights (2018)
* Manufacturing job: Increasing number of jobs. The number and nature of jobs will never be the same.
* White color job: Expert-Automation & Augmentation Software (EAAS). AI-enhanced productivity changes industries such as law, media, wealth management, etc.
  * NLP startups in legal industry such as ROSS, Legal Sifter, Casetext, LawGeex. AI can summarize thousands of pages of legal documents within minutes.
  * Software development: Applitools, DiffBlue (UK) provides AI based software testing, debugging and basic front-end development.
* AI talent wars: Everyone is on the hiring spree.
  * Average salary of $350K at DeepMind. ~$600K for Sr. ML researcher at BMW China.
* AI for everything: Weed, Fish, Horses (HoofStep), Beer Brewing
* ML gets normalized.
* Amazon, Google and Microsoft dominate enterprise AI
* AI diagnostics
  * Healthcare AI deals top the chart - hottest area of AI startup investment
  * Fueled by medical imaging and diagnostic companies: Arterys that analyzes cardiac images raised $42M at valuation at $82M
  * Strategic partnerships: NVidia + GE, DeepMind + NHS, AliHealth + AstraZeneca

#### [Artificial Intelligence - The Next Digital Frontier?](https://www.mckinsey.com/~/media/McKinsey/Industries/Advanced%20Electronics/Our%20Insights/How%20artificial%20intelligence%20can%20deliver%20real%20value%20to%20companies/MGI-Artificial-Intelligence-Discussion-paper.ashx) by McKinsey Global Institute (2017)
* AI is getting ready for business, but are businesses ready for AI?
  * Tech giants spent $20B ~ $30B on AI in 2016: 90% on R&D + 10% on AI acquisitions
  * VC and PE financing, grants and seed investments invested $6B ~$9B on AI
  * Outside of tech sector, only 20% currently use any AI-related technology at scale
  * A successful program requires: identify the business case, set up the right data ecosystem, build or buy appropriate AI tools, and adapt workflow processes, capabilities, and culture. Leadership from the top, management and technical capabilities, and seamless data access are key enablers.
* AI promises to boost profits and transform industries
* Businesses, developers and governments need to act now to realize AI's full potential
* Case studies: AI's potential to improve forecsting and sourcing, optimize and automate operations, develop targeted marketing and pricing and enhance the user experience
  * Retail
  * Electric utility
  * Manufacturing
  * Healthcare
  * Education

## BY INDUSTRIES

### Healthcare

#### [Neural Interfaces: Connecting humans and AI](https://www.youtube.com/watch?v=5Z5aZK2C3ew) by Thomas Reardon at Oreilly's AI Conference in NY (2018)

### Social Good

#### [Towards Globally Beneficial AI](https://www.facebook.com/ijcaiecai18/videos/2192356910905283/UzpfSTEwMDAwMDc3MDUxMDg5OToyMDAxNDI0MTA5ODkxNjg5/) by Stefano Ermon at IJCAI (2018)
* Recent progress in AI: Computer vision, speech recognition, game playing, machine translation, theorem proving, question answering, etc.
* 17 sustainable development goals
* Large scale economic modeling: Jean, Ermon et al. Science 2016
  * Geo statistics --> Deep Gaussian process
  * Semi-supervised learning
  * Predicts crop productivity, infrastructure quality, population density, crop disease, etc.
* Learnging with limited labeled data/supervision
  * Learning from constraints (AAAI-17 best paper)
  * Generative models
  * Semi-supervised learning and domain adaptation
* Uncertainty quantification: Recalibration (AAAI-17, ICML-18)


## BY COMPANIES

### Microsoft

#### Healthcare
* [Democratizing AI in Healthcare](http://www.democratizing-ai-in-health.com/)
* [Healthcare NExT](http://www.businessinsider.com/peter-lee-microsoft-research-healthcare-next-interview-2018-2): Fusing research, AI and industry expertise through partners
* [InnerEye](https://www.microsoft.com/en-us/research/project/medical-image-analysis/)
  * Automatic 3D segmentation of tumor and healthy cells
  * Better understanding of cancer response
  * Human + machine - AI assistance for planning radiotherapy treatments
  * Can be deployed as intelligent Azure services
  * Demo on automatic brain tumor segmentation at RSNA-2017
* [EmpowerMD](https://www.microsoft.com/en-us/research/project/empowermd/)
  * Intelligent Scribe
  * Transcription, entity, intent, synthesis phrases. Important phrases from patient speech.
  * Rancked by confidence level
  * Collaboration with UPMC (University of Pittsburgh Medical Center)
* [Microsoft Genomics Service](https://azure.microsoft.com/en-us/services/genomics/)
  * St. Jude Children's Research Hospital
  * Cloud implentation of BWA and Genome Analysis Toolkit (GATK)
* [Health Bot](https://www.microsoft.com/en-us/research/project/health-bot/)
  * Access health data with conversational intelligence
  * Insurers uses bots to give customers an easy way to look up the status of a claim and ask questions about benefits
  * Providers uses bots to triage patient issues with symptom checker, help patients find care, and look up nearby doctors.
  * Partners: Premera Blue Cross, Aurora Healthcare, Health Navigator, UPMC
* [Enable Group at MSR](https://www.microsoft.com/en-us/research/group/enable/)
  * [Eye-controlled user interface in Windows 10](https://support.microsoft.com/en-us/help/4043921/windows-10-get-started-eye-control)
  * [Soundscape](https://www.microsoft.com/en-us/research/product/soundscape/): Sound-based user interface 
* [Ability Group at MSR](https://www.microsoft.com/en-us/research/group/ability/): R&D innovative technologies that extend the capabilities of and enhance quality of life for people with disabilities
* [Lung cancer prediction with search queries](https://blogs.microsoft.com/ai/microsoft-researchers-detect-lung-cancer-risks-web-search-logs/)
* [Project Hanover](https://news.microsoft.com/stories/computingcancer/): For machine reading, cancer decision support, chronic disease management. Collaboration with Knight Cancer Institute.
* Heart disease detection: Collaboration with India's Apollo Hospitals


### Google

### Amazon

### Facebook


## BY RESEARCH AREAS

### Computer Vision

### Natural Language Process

#### Machine Reading Comprehension (MRC)

* [ReasoNet + R-NET](https://www.ailab.microsoft.com/experiments/ef90706b-e822-4686-bbc4-94fd0bca5fc5) by Microsoft Research

### Ethics

#### [The Trouble with Bias](https://www.youtube.com/watch?v=fMym_BKWQzk) Keynote by Kate Crawford at NIPS (2017)

#### [AI Now 2017 Report](https://ainowinstitute.org/AI_Now_2017_Report.pdf) by [AI Now Institute](https://ainowinstitute.org) (2017)
* Labor and automation
* Bias and inclusion
* Rights and liberties
* Ethics and governance

## CRITICISMS (a.k.a. HYPE BUSTERS)

#### [Why Everyone Is Hating on IBM Watson](https://gizmodo.com/why-everyone-is-hating-on-watson-including-the-people-w-1797510888) by Jennings Brown at Gizmodo (2017)

#### [Google's AutoML: Cutting Through the Hype](http://www.fast.ai/2018/07/23/auto-ml-3/) by Rachel Thomas at fast.ai (2018)

#### [Has AI Surpassed Humans at Translation? Not Even Close!](https://www.skynettoday.com/editorials/state_of_nmt) by Sharon Zhou at Skynet Today (2018)

#### [Deep Learning: A Critical Appraisal](https://arxiv.org/abs/1801.00631) by Gary Marcus at arXiv.org (2018)

#### [Innateness, AlphaZero, and Artificial Intelligence](https://arxiv.org/abs/1801.05667) by Gary Marcus at arXiv.org (2018)

#### [AI Winter is Well on Its Way](https://blog.piekniewski.info/2018/05/28/ai-winter-is-well-on-its-way/) by Filip Piekniewski (2018)

#### [Rebooting AI - Postulates](https://blog.piekniewski.info/2018/06/20/rebooting-ai-postulates/) by Filip Pienkniewski (2018)

## REFERENCES

### AI General
* [Awesome Artificial Intelligence](https://github.com/hades217/awesome-ai) compiled by Lightman Wang

### Research
* [Deep Learning Papers by Task](https://github.com/sbrugman/deep-learning-papers) compiled by Simon Brugman