<h1>Internal AI Service Provider/COE</h1>

<p>When implementing AI within a company, a common pattern is to have one group take the lead. This is often central IT, but not always; a key business unit can work just as well. There are many aspects to rolling this structure forward, and this blog will discuss many of them to ensure you have a plan, or at least a way to think about each of them.</p>

<h2>Responsibilities for a COE (Center of Excellence)</h2>
 [Identify guiding principles for responsible AI]:(https://docs.microsoft.com/en-us/learn/modules/responsible-ai-principles/index)

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com


 
<ol>
<li><p><strong>Vetting Application Portfolio:</strong></p>

<ul>
<li>Responsible for assessing applications from individual business units for corporate fit. This process often involves quantifying business value and technical capability, plotting them along the x and y axis to prioritize applications. Items in the top right quadrant are approved first. Sometimes, the COE may simply provide feedback, leaving the final decision to each business unit.</li>
<li><strong>Key links:</strong> Azure Application Insights, [Azure Advisor](http://microsoft.com/),  [Identify guiding principles for responsible AI](https://docs.microsoft.com/en-us/learn/modules/responsible-ai-principles/index)</li>
</ul></li>
<li><p><strong>Guidance on AI Application Development:</strong></p>

<ul>
<li>Providing advice to other business units on how to craft applications using generative/classical AI. Many application development teams excel in web development but lack expertise in generative AI. The COE can offer tips and guidance, especially for current search and RAG (Retrieval-Augmented Generation) patterns prevalent in AI/GenAI applications.</li>
<li><strong>Key links:</strong> Azure AI Services, Azure Machine Learning</li>
</ul></li>
<li><p><strong>Strong LMMOps Model and Process:</strong></p>

<ul>
<li>Ensuring a robust model for managing machine learning operations (MLOps), specifically for large language models (LLMs). This includes monitoring, maintaining, and updating models to ensure they meet the company's standards and needs. Moving models to production is key.</li>
<li><strong>Key links:</strong> Azure MLOps, Azure DevOps</li>
</ul></li>
<li><p><strong>Model Management:</strong></p>

<ul>
<li>Managing models across business units can become complex. A centralized COE can streamline testing new models and maintaining an internal model catalog, aiding in adoption and future-proofing.</li>
<li><strong>Key links:</strong> Azure OpenAI Service, Azure Machine Learning Model Management</li>
</ul></li>
<li><p><strong>Testing of New Models:</strong></p>

<ul>
<li>The COE should handle the evaluation and testing of new AI models to ensure they meet the company's performance and ethical standards before deployment.</li>
<li><strong>Key links:</strong> Azure Machine Learning Model Evaluation, Azure DevTest Labs</li>
</ul></li>
<li><p><strong>Key Management:</strong></p>

<ul>
<li>Overseeing the management of cryptographic keys used in AI systems to ensure security and compliance with company policies.</li>
<li><strong>Key links:</strong> Azure Key Vault, Azure Security Key Management</li>
</ul></li>
<li><p><strong>API Management:</strong></p>

<ul>
<li>Managing APIs to ensure they are secure, efficient, and meet the needs of various business units. This includes version control and monitoring API usage.</li>
<li><strong>Key links:</strong> Azure API Management, Azure API Gateway</li>
</ul></li>
<li><p><strong>Agentic Framework:</strong></p>

<ul>
<li>Establishing frameworks for AI agents that can autonomously perform tasks, ensuring they align with business goals and ethical standards.</li>
<li><strong>Key links:</strong> Azure Bot Service, Azure AI Agent</li>
</ul></li>
<li><p><strong>Fine-Tuning Guidance:</strong></p>

<ul>
<li>Providing guidelines for fine-tuning AI models to better suit specific business needs without compromising performance or safety.</li>
<li><strong>Key links:</strong> Azure Machine Learning - Fine-tuning models, Azure Custom Vision</li>
</ul></li>
<li><p><strong>Unified Model for Content Safety:</strong></p>

<ul>
<li>Developing a unified approach to content safety to prevent the dissemination of harmful or inappropriate content generated by AI models.</li>
<li><strong>Key links:</strong> Azure Content Moderator, Azure Security Center</li>
</ul></li>
<li><p><strong>Consistent Implementation of Responsible AI Principles:</strong></p>

<ul>
<li>Ensuring all AI projects adhere to the company's Responsible AI principles, promoting ethical and fair AI usage.</li>
<li><strong>Key links:</strong> Microsoft Responsible AI, Azure AI Ethics and Responsible AI</li>
</ul></li>
<li><p><strong>Error Handling and Control:</strong></p>

<ul>
<li>Establishing protocols for identifying, reporting, and mitigating errors in AI systems to maintain reliability and trust.</li>
<li><strong>Key links:</strong> Azure Monitor, Azure Application Insights</li>
</ul></li>
<li><p><strong>Support for GenAI/Ticketing:</strong></p>

<ul>
<li>Providing support and a ticketing system for issues related to large language models, ensuring quick resolution and continuous improvement.</li>
<li><strong>Key links:</strong> Azure Support Plans, Azure Service Health</li>
</ul></li>
<li><p><strong>Legal Indemnification Requirements:</strong></p>

<ul>
<li>Managing legal risks associated with AI usage, ensuring compliance with regulations, and protecting the company from potential liabilities.</li>
<li><strong>Key links:</strong> Microsoft AI Legal, Microsoft AI Compliance</li>
</ul></li>
<li><p><strong>Corporate Compliance:</strong></p>

<ul>
<li>Ensuring AI projects comply with corporate rules and regulations, including data privacy laws and industry-specific standards.</li>
<li><strong>Key links:</strong> Azure Compliance Offerings, Microsoft Compliance Manager</li>
</ul></li>
<li><p><strong>Cost Containment and Resource Utilization:</strong></p>

<ul>
<li>Planning and managing the costs associated with AI projects, optimizing resource utilization and capacity planning to prevent overspending.</li>
<li><strong>Key links:</strong> Azure Cost Management, Azure Capacity Planning</li>
</ul></li>
<li><p><strong>Efficient Use of GenAIs:</strong></p>

<ul>
<li>Large language models can be expensive if not used appropriately. The COE should ensure efficient and effective use to maximize ROI.</li>
<li><strong>Key links:</strong> Azure Machine Learning Cost Management, Azure AI Optimization</li>
</ul></li>
<li><p><strong>Chargebacks to Business Units:</strong></p>

<ul>
<li>Implementing a chargeback system where business units are billed based on their usage level and the specific services they utilize.</li>
<li><strong>Key links:</strong> Azure Cost Management + Billing, Azure Tagging for Chargebacks</li>
</ul></li>
<li><p><strong>Security Implementation:</strong></p>

<ul>
<li>Ensuring top-notch security, potentially using services like Entra, to protect AI systems and data.</li>
<li><strong>Key links:</strong> Azure Active Directory (Entra), Azure Security Center</li>
</ul></li>
<li><p><strong>Independent Software Vendors (ISVs):</strong></p>

<ul>
<li>Approving third-party software or SaaS systems and tools for use within the company, ensuring they meet security and performance standards.</li>
<li><strong>Key Links:</strong> Azure Marketplace, Microsoft Partner Network</li>
</ul></li>
<li><p><strong>Approved System Integration (SI) Partners:</strong></p>

<ul>
<li>Vetted SI partners with expertise in your business and AI can be crucial for developing and deploying generative AI applications into production.</li>
<li><strong>Key Links:</strong> Azure SI Partners, Microsoft AI Partners</li>
</ul></li>
<li><p><strong>Lightweight Service Provisioning:</strong></p>

<ul>
<li>Providing a service that simply offers provisioning without additional assistance or commentary, for teams that prefer a more hands-on approach.</li>
<li><strong>Key Links:</strong> Azure Resource Manager, Azure Automation</li>
</ul></li>
</ol>

<h2>LLM/GenAI Business Value</h2>

<p><strong>1. Enhanced Decision Making:</strong>
   - AI-driven insights provide a deeper understanding of business operations and market trends, enabling better and faster decision-making processes.</p>

<p><strong>2. Increased Efficiency:</strong>
   - Automating routine tasks with AI frees up human resources for more strategic work, improving overall productivity and reducing operational costs.</p>

<p><strong>3. Personalized Customer Experiences:</strong>
   - Leveraging AI to analyze customer data can lead to highly personalized interactions, increasing customer satisfaction and loyalty.</p>

<p><strong>4. Innovation and Competitive Advantage:</strong>
   - Implementing cutting-edge AI solutions can foster innovation, providing a significant competitive edge in the marketplace.</p>

<p><strong>5. Cost Reduction:</strong>
   - AI can optimize resource allocation and reduce waste, leading to substantial cost savings across various business functions.</p>

<p><strong>6. Risk Management:</strong>
   - AI can enhance risk management by predicting potential issues and enabling proactive measures to mitigate them.</p>

<p><strong>7. Scalability:</strong>
   - AI systems can handle large-scale operations efficiently, allowing businesses to scale their operations without a proportional increase in costs.</p>

<h2>Conclusion</h2>

<p>This can be a daunting checklist. Once you determine which items are key for your corporate AI Service Provider function, we are happy to have specific discussions around each or review your architecture as a whole. If you do not wish to centralize these functions, the first business unit to roll out generative AI solutions can offer a "blueprint" documenting their approach. This can help new business units avoid common pitfalls and ensure a smoother implementation process. Starting from scratch is challenging, and many teams forget one or more of these crucial elements.</p>

<p>Thank you!</p>


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
