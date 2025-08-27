## Hi there 👋

<!--
**ai-systems-security/ai-systems-security** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# AI Systems Security Experiments 🛡️🤖

[![Profile Views](https://komarev.com/ghpvc/?username=ai-systems-security&color=blue)](https://github.com/ai-systems-security)  [![GitHub followers](https://img.shields.io/github/followers/ai-systems-security?label=Follow&style=social)](https://github.com/ai-systems-security?tab=followers)  [![GitHub stars](https://img.shields.io/github/stars/ai-systems-security?style=social)](https://github.com/ai-systems-security)

Welcome to my **AI Systems Security Experiments** profile! This repository collection explores **security risks in AI Agents** and **adversarial machine learning in financial AI systems**.  Hands-on projects demonstrate vulnerabilities in multi-agent systems, unsafe AI operations, and adversarial attacks on machine learning models.

---

## 🚀 Highlights

### Attacking Insecure Agents
- Excessive Database Agency: LLMs issuing unrestricted queries like `MATCH (n) RETURN n` on Neo4j.  
- Multi-Agent Manipulation: Prompt-engineered attacks influencing collaborative AI agents.  
- Prompt Injection & Policy Bypass: Tricks agents into leaking sensitive information.  
- Unsafe Tool Execution: Exploits AI agents with unrestricted tool access.

### Financial AI Security
- Evasion attacks on credit scoring models (tabular data).  
- Black-box and white-box attacks using ART and Foolbox.  
- Future roadmap includes model extraction, inference attacks, poisoning, and defenses.  

### 🎯 Goals
- Simulate real-world attacks on AI agents and financial AI systems.  
- Explore mitigations: guardrails, whitelisting, monitoring, robust training.  
- Provide a hands-on learning environment for AI security research.

---

### ⚒️ Tools & Tech 

**AI/ML & Security Frameworks**  

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)  [![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)  [![PyTorch](https://img.shields.io/badge/PyTorch-black?logo=pytorch&logoColor=orange)](https://pytorch.org/)  [![ART](https://img.shields.io/badge/ART-Adversarial%20Robustness%20Toolbox-green?logo=ibm&logoColor=white)](https://adversarial-robustness-toolbox.readthedocs.io/)  [![Foolbox](https://img.shields.io/badge/Foolbox-red?logo=github&logoColor=white)](https://foolbox.readthedocs.io/)  [![SecML](https://img.shields.io/badge/SecML-purple?logo=github&logoColor=white)](https://secml.readthedocs.io/en/v0.15/)  [![PrivacyRaven](https://img.shields.io/badge/PrivacyRaven-gray?logo=github&logoColor=white)](https://github.com/trailofbits/PrivacyRaven)  [![TextAttack](https://img.shields.io/badge/TextAttack-red?logo=openai&logoColor=white)](https://textattack.readthedocs.io/en/master/)  [![PromptBench](https://img.shields.io/badge/PromptBench-purple?logo=github&logoColor=white)](https://github.com/microsoft/promptbench)  [![LlamaFirewall](https://img.shields.io/badge/LlamaFirewall-FF4500?logo=github&logoColor=white)](https://github.com/YourRepo/LlamaFirewall)

**Databases & Graphs**  

[![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?logo=neo4j&logoColor=white)](https://neo4j.com/)  [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)](https://www.postgresql.org/)  

**LLM & Agents**  

[![LangChain](https://img.shields.io/badge/LangChain-black?logo=chainlink&logoColor=blue)](https://www.langchain.com/)  [![LangGraph](https://img.shields.io/badge/LangGraph-orange?logo=python&logoColor=white)](https://github.com/langgraph/langgraph)  [![Ollama](https://img.shields.io/badge/Ollama-000000?logo=github&logoColor=white)](https://ollama.com/)  [![LLaMA](https://img.shields.io/badge/LLaMA-FF4500?logo=meta&logoColor=white)](https://ai.meta.com/llama/)

**Security Standards & Regulatory Compliance**  

[![OWASP LLM Top 10](https://img.shields.io/badge/OWASP-LLM%20Top--10-red?logo=owasp&logoColor=white)](https://owasp.org/www-project-top-10-for-large-language-model-applications/)  [![OWASP ML Top 10](https://img.shields.io/badge/OWASP-ML%20Top--10-purple?logo=owasp&logoColor=white)](https://owasp.org/www-project-machine-learning-security-top-10/)  [![OWASP Agentic AI Threats](https://img.shields.io/badge/OWASP-Agentic--AI--Threats-orange?logo=owasp&logoColor=white)](https://genai.owasp.org/resource/agentic-ai-threats-and-mitigations/)  [![NIST AI RMF](https://img.shields.io/badge/NIST-AI%20RMF-blue?logo=gov&logoColor=white)](https://www.nist.gov/itl/ai-risk-management-framework)  [![MITRE ATLAS](https://img.shields.io/badge/MITRE-ATLAS-red?logo=mitre&logoColor=white)](https://atlas.mitre.org/)[![GDPR AI](https://img.shields.io/badge/GDPR-AI-blue?logo=gdpr&logoColor=white)](https://gdpr-info.eu/)  [![ISO/IEC 42001:2023](https://img.shields.io/badge/ISO--IEC%2042001:2023-green?logo=iso&logoColor=white)](https://www.iso.org/standard/42001)  

### Running Experiments
- Agent experiments: `jupyter notebook: excessive_db_agency1.ipynb, excessive_db_agency2.ipynb`  
- Adversarial ML on credit scoring: `jupyter notebook: bim_attack-art-logistic_regression.ipynb, cw_attack-art-logistic_regression.ipynb, deepfool_attack-art-logistic_regression.ipynb, ead_attack-art-logistic_regression.ipynb, fgm_attack-art-logistic_regression.ipynb, jsma_attack-art-logistic_regression.ipynb, pgd_attack-art-logistic_regression.ipynb, boundary _attack(targeted)_attack-art-logistic_regression.ipynb, boundary _attack(untargeted)_attack-art-logistic_regression.ipynb, hsj_attack-art-logistic_regression.ipynb, zoo_attack-art-logistic_regression.ipynb`

---

## 📊 GitHub Stats
![ai-systems-security's GitHub stats](https://github-readme-stats.vercel.app/api?username=ai-systems-security&show_icons=true&hide_title=true&count_private=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ai-systems-security&layout=compact&theme=radical)

---

## ⚠️ Security Notes
- For **educational purposes only**.  
- Do **not deploy vulnerable agents** or ML models in production.  
- Always enforce: whitelisting, tool guardrails, interaction monitoring, policy & prompt security, adversarially robust ML defenses.

---

## 📚 References
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-llm-applications/)  
- [OWASP ML Security Top 10 (2023)](https://owasp.org/www-project-machine-learning-security-top-10/)  
- [LangGraph Documentation](https://python.langchain.com/docs/langgraph)  
- [Neo4j Graph Database](https://neo4j.com/)  
- [Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)  
- [Agentic AI research papers & security advisories]  

---

Thanks for visiting my profile! 👋
