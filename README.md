### Muhkam – Intellectual Property Platform Powered by AI
Muḥkam is an Arabic platform powered by artificial intelligence, built using the ALLAM large language model, and specialized in Saudi Arabian intellectual property (IP) law. The platform aims to support lawyers, law students, and everyday users by answering their questions related to IP rights and legal inquiries. 

###	**Introduction**
In recent years, artificial intelligence (AI)  has revolutionized how machines understand, produce, and interact with human language. Generative AI, more specifically large language models (LLMs), has shown substantial advancement in areas such as question-answering, summarisation, and chatbot systems. Technologies like these are expanding in so many fields, including education, healthcare, and even law,  providing crucial assistance with specialized knowledge. Although these technologies have witnessed widespread usage in English and other prominent languages, their application in specialized fields like law is still limited, specifically in Arabic. 
In Saudi Arabia, individuals and small business owners lack direct access to reliable answers and face hardships when it comes to obtaining dependable and legal counsel concerning Intellectual Property (IP) rights. The traditional methods of legal advice, typically involving consultations, tend to be expensive and protracted, thereby presenting an obstacle for those aiming to understand their legal standing. Even for a law student, the process of seeking knowledge from a trustworthy place could be challenging and time-consuming. This difficulty underscores a rising demand for AI-based legal solutions, which have to be accessible, credible, and provided in a language that the user understands.
This study introduces Muḥkam, a generative AI chatbot tailored for Arabic speakers seeking information on Saudi Arabian intellectual property law. It's built on a Retrieval-Augmented Generation (RAG) framework, effectively merging document retrieval with a generative model. Consequently, it's designed to offer precise and contextually relevant answers. The key feature is its reliance on authoritative, verified legal resources to formulate its responses to user inquiries.

###	**Literature Review**
Alkhalifa et al. [1] proposed ALLaM, a family of multilingual big language models created by the National Center for AI (NCAI) under the Saudi Data and AI Authority (SDAIA), to advance natural language processing in Arabic and English. The authors focused on the underrepresentation of Arabic in existing LLMs through using two core pretraining strategies: continued pretraining of English-centric models such as Falcon on Arabic-rich corpora, and training from scratch with a multilingual dataset containing over two trillion tokens, balanced between Arabic and English. To improve model consistency with human standards, supervised fine-tuning (SFT) and Direct Preference Optimization (DPO) were used, allowing the model to deliver more appropriately suited and culturally sensitive results. The models were evaluated via a combination of automatic benchmarks, such as the Massive Multitask Language Understanding (MMLU) benchmark and its Arabic adaptation, MMLU Arabic, as well as the Arabic Cultural and Values Alignment (ACVA) benchmark, which evaluates the cultural relevance and value alignment in generated responses. ALLaM outperformed prior Arabic and multilingual models such as AraBERT and CAMeLBERT, demonstrating cutting-edge performance on numerous Arabic-specific tasks. This work made a substantial contribution to the development of inclusive and linguistically varied AI by integrating rigorous multilingual training with culturally conscious assessment and alignment procedures. 
Ammar et al. [2] proposed a unique use of large language models (LLMs) for predicting court verdicts in Arabic, a subject that is mostly unexplored in natural language processing (NLP). The study examined the linguistic and contextual difficulties of Arabic legal documents using a dataset of 10,813 real-world commercial court cases from Saudi Arabia. The researchers tested three popular LLMs—LLaMA-7b, JAIS-13b, and GPT-3.5-turbo—under a variety of training regimes, including zero-shot, one-shot, and fine-tuned settings. They also looked at the effect of preprocessing procedures like case summaries and English translation on model performance. ROUGE and BLEU measures were used to assess performance, along with GPT-based grading and human expert review. Notably, GPT-3.5-turbo outscored the Arabic-specific JAIS-13b and the multilingual LLaMA-7b, with average scores up to 50% higher in key evaluation categories. Despite GPT-3.5's great performance, the authors discovered errors in automated measures, emphasizing the importance of trustworthy human evaluation in legal NLP applications. This study adds to the emerging field of AI in law by demonstrating that, when combined with proper preprocessing and assessment approaches, LLMs may enhance Arabic judicial decision-making, making them a viable tool for improving efficiency and accessibility in legal analytics.

 
## Target Audience
1.	Lawyers, law students, and legal professionals
2.	IP rights holders and content creators
3.	General users interested in their intellectual property rights
 
## Key Features
1.	For legal professionals: Ask Muhkam detailed legal questions and receive accurate answers based on the Saudi Copyright Law and IP Regulations.
2.	For general users: Ask Muhkam any question about IP rights in Saudi Arabia in simple, understandable language.
 
## Technologies Used
•	ALLAM Model: The core Arabic language model powering the chatbot.
•	Prompt Engineering: Used to fine-tune user prompts and ensure accurate, legal context-aware responses.
•	Retrieval-Augmented Generation (RAG): Combined with ElasticSearch to retrieve precise legal information from trusted documents and feed it to the model.

## Model Architecture
**Muhkam uses a hybrid RAG architecture:**
• A retriever (ElasticSearch) fetches relevant Saudi IP laws and regulations.
• A fine-tuned generative model (ALLAM) generates user friendly answers based on retrieved texts.

**Model Components**
• User query → Retriever (ElasticSearch) → Retrieved documents → Generator (ALLAM).

## Quantitative Results
ROUGE-L Score: 0.68






## مُحكم - منصة حقوق الملكية الفكرية باستخدام الذكاء الاصطناعي

**مُحكم** هي منصة عربية تعتمد على الذكاء الاصطناعي باستخدام نموذج **علام (ALLAM)** المختص في مجال حقوق الملكية الفكرية السعودية. تهدف المنصة إلى مساعدة المحامين، الطلاب، والمستخدمين العاديين في الإجابة على أسئلتهم المتعلقة بحقوق الملكية الفكرية أو أي استفسارات تتعلق بحقوقهم الفكرية. بالإضافة إلى ذلك، توفر المنصة خاصية توليد مستندات حقوق الملكية الفكرية للمؤلفين.

## الجمهور المستهدف
1.  المحامين وطلاب القانون وموظفيّ الهيئات
2.  مؤلف للملكية
3.  مستخدمون آخرون 
## الميزات
1.  للجمهور الأول:الاستفسار من مُحكم لإعطاءهم شرح مفصل حول الاستفسار أو السؤال حول المواد القانونية ممَا يتعلق بنظام حقوق المؤلف ولائحة النظام للملكية الفكرية"
2.  للجمهور الثاني: سؤال مُحكم عن أي شيء متعلق بنظام حقوق المؤلف ولائحة النظام للملكية الفكرية


## التقنيات المستخدمة
د- **ALLAM Model**: النموذج الأساسي للذكاء الاصطناعي المستخدم في المنصة.
- **هندسة التوجيهات (Prompt Engineering)**: تم استخدامها لضبط التوجيهات لضمان الحصول على إجابات دقيقة.
- **استرجاع المعلومات المعززة (RAG)**: باستخدام **ElasticSearch** لتحسين دقة وسرعة استرجاع البيانات القانونية.

## البيانات المستخدمة
في هذا المشروع، تم استخدام البيانات الرسمية من:
- **لائحة النظام - من هيئة الخبراء بمجلس الوزراء**
- **نظام حماية حقوق المؤلف - الهيئة السعودية للملكية الفكرية**

