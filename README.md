## Muhkam – Intellectual Property Platform Powered by AI
Muḥkam is an Arabic platform powered by artificial intelligence, built using the ALLAM large language model, and specialized in Saudi Arabian intellectual property (IP) law. The platform aims to support lawyers, law students, and everyday users by answering their questions related to IP rights and legal inquiries. 

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

