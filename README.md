# mlops-weaviate-workshop
# **Setting Up Weaviate Workshop**

## **Getting API Keys:**

### **1. Weaviate Cloud:**

- Create a cloud account [here](https://console.weaviate.cloud/).
- Create a sandbox cluster [here](https://console.weaviate.cloud/dashboard).
- Next to your cluster, click "Details," and then select "API Keys."
- Copy your **API Key** and **Cluster URL**.

### **2. Cohere:**

- Register [here](https://dashboard.cohere.com/welcome/register).
- Get your API Key from [here](https://dashboard.cohere.com/api-keys).

### **3. Open AI:**

- Copy your API key from [here](https://platform.openai.com/account/api-keys).

Update .env with api keys

## **GitHub Setup:**

1. Login to your GitHub account.
2. Go to this repository: [mlops-weaviate-workshop](https://github.com/majamil16/mlops-weaviate-workshop/tree/main).
3. Click on ‘Code’ > Codespaces.
4. You will see a section labeled "Codespaces" with options “**+**” and “**…**” to the right. Click “**…**,” and then select “**New with Options**.”
5. Upgrade the **Machine type** to “**4-core**.”
6. Click "Create codespace."
7. It may take a few minutes for your Codespaces container to start. Once it does, you will see the IDE, terminal, and repository similar to VSCode.
8. Run the command **`docker compose up`**.
9. After a few minutes, you should see a message like this:
"**mlops-weaviate-workshop-multi2vec-bind-1 | INFO: 172.19.0.3:48294 - "GET /meta HTTP/1.1" 200 OK**.”

You’re all set!

Note: You might be guided through Python, Docker, and Jupyter extension installations within Codespaces.
