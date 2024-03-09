# 102 Essentials 

## AI essentials
If you are completely new to AI, you should have elementary ML knowledge, especially with terms: supervised ML, unsupervised ML, reinforcement learning, probability, confidence scores, model training and inferencing. 
The notes compiled in the images are from the [Microsoft Learn's](https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-102/) page.  
- Probability and Confidence scores
- Model Training and Inferencing
- Multiclass, Multilabel

![azure AI basics](https://raw.githubusercontent.com/blessinvarkey/ai-102-2024-notes/main/assets/essentials0.png)


## Responsible AI 
- Fairness
- Reliability and safety
- Privacy and security
- Inclusiveness
- Transparency 
- Accountability

## Azure Subscription/Resource
- Resource: There are two keys generated (Check Keys and Endpoint). Rotate between the two keys for uninterrupted service. Always need to know the endpoint URLs and the region. 
- Multi-service: single endpoint, single access credential for all services
- Single-service: single endpoint, single access credential per service. (separate billing for each service)  

## Endpoint URLs
- Firewall: Public IPs, Service endpoint (tag specific subnets in a virtual network), Private endpoint   

```  
COG_SERVICE_ENDPOINT=your_cognitive_services_endpoint
COG_SERVICE_KEY=your_cognitive_services_key
``` 

## Running the container
- Accept EULA: accept


## Azure Key Vault
- You can store the two keys in the Azure key vault. Can apply RBAC. 

## Azure AI Services
The essential Azure AI services are as follows: 
- Natural Language Processing
- Knowledge Mining and Document Intelligence 
- Computer Vision
- Generative AI 
![azure AI services](https://raw.githubusercontent.com/blessinvarkey/ai-102-2024-notes/main/assets/essentials1.png)

