# Hands-on workshops

## On https://developers.redhat.com/
This environment (sandbox) is always available. You just need to register

**Workshops:**
* [Local ChatGPT - consuming](https://developers.redhat.com/learn/ai/get-started-consuming-gpu-hosted-large-language-models-developer-sandbox)
* [Local number recognition - training](https://github.com/maarten-vandeperre/hello-world-NN)
  * It is possible that you run into missing dependencies, in that case, add the following pip installs in blocks in the Jupyter Notebook:
    * %pip install torch torchvision matplotlib numpy
    * %pip install onnx onnxscript
 
## On dedicated environment (feel free to request one)

### Parasol - AI platform, model training, deployment and integration in app
https://catalog.demo.redhat.com/workshop/mt9gqe

Explore how the fictional insurance company, Parasol, uses OpenShift AI to improve its claims processing. In this immersive experience, you will have the opportunity to deploy and work with different AI models while utilizing various features of OpenShift AI.

### Model as a service

https://catalog.demo.redhat.com/workshop/fht5tk

Red Hat OpenShift AI provides a Models-as-a-Service architecture that enables centralized model management, secure API gateways, and developer-friendly access without GPU complexity. This hands-on workshop rotates participants through three personas: as a developer, access model credentials and integrate AI code assistants into your workflow; as an SRE/DevOps practitioner, explore agentic AI with Model Context Protocol (MCP) servers to interact with OpenShift and Slack using natural language; as a decision maker, monitor model usage analytics with Grafana to understand cost, capacity, and business impact.
