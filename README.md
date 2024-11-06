# Azure OpenAI Data Generator  
  
Welcome to the Azure OpenAI Data Generator repository! This project leverages Azure OpenAI to automatically generate datasets for various use cases. With this tool, you can quickly create datasets that include product titles, descriptions, prices, and even images.  
  
## Features  
  
- **Automatic Data Generation**: Generate datasets for various domain.  
- **Customizable**: Define the number of items and customize the dataset as per your requirements.  
- **Scalable**: Leverage the power of Azure OpenAI to generate large-scale datasets efficiently.  
  
## Getting Started  
  
### Prerequisites  
  
- An Azure account with access to Azure OpenAI services.  
- Node.js installed on your local machine.  
- Azure CLI installed and configured.  
  
### Installation  
  
1. Clone the repository:  
  
    ```sh  
    git clone https://github.com/liamca/gpt4-data-generator.git
    cd gpt4-data-generator  
    ```  
  
2. Install dependencies:  
  
    ```sh  
    pip install -r requirements.txt  
    ```  
  
3. Set up your Azure OpenAI environment. Follow the [Azure OpenAI documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/openai/) to create and configure your Azure OpenAI resource.  
  
4. Create a `.env` file in the root directory and add your Azure OpenAI credentials:  
  
    ```plaintext  
    AZURE_OPENAI_ENDPOINT=your_openai_endpoint  
    AZURE_OPENAI_API_KEY=your_openai_api_key  
    ```  
  
### Usage  
  
To generate a product dataset, ...
