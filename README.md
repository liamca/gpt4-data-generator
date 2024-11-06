# Azure OpenAI Product Data Generator  
  
This project leverages Azure OpenAI to automatically generate datasets for various use cases. With this tool, you can quickly create datasets that include product titles, descriptions, prices, and even images. The output will be stored in JSON format.
  
## Features  
  
- **Automatic Product Data Generation**: Generate product datasets (which can be altered for various domains).  
- **Customizable**: Define the number of items and customize the dataset as per your requirements.  
- **Scalable**: Leverage the power of Azure OpenAI to generate large-scale datasets efficiently.  

### Example Output

```json
{
"Category": "Electronics",
"Subcategory": "Mobile Phones",
"Title": "ContosoMax Pro 5G Smartphone",
"Description": "# ContosoMax Pro 5G Smartphone – Available at Contoso Retail\n\n## Overview\n\nExperience the future of mobile technology today with the ContosoMax Pro 5G Smartphone, exclusively available at Contoso Retail. This cutting-edge device redefines excellence in the world of smartphones, offering unbeatable performance, stunning design, and unparalleled connectivity. Whether you're a tech enthusiast, a professional on the go, or a casual user, the ContosoMax Pro 5G is designed to meet all your needs with finesse and style.\n\n## Key Features\n\n### Blazing-Fast 5G Connectivity\nStay ahead of the curve with next-generation 5G connectivity. Enjoy lightning-fast downloads, seamless streaming, and superior network reliability. The ContosoMax Pro 5G ensures you're always connected at top speeds, no matter where you are.\n\n### Brilliant Display\nImmerse yourself in vibrant colors and crystal-clear visuals with the 6.7-inch Super AMOLED display. Whether you're watching videos, playing games, or browsing the web, the Full HD+ resolution ensures a stunning visual experience.\n\n### Powerful Performance\nEquipped with the latest Octa-core processor and 8GB of RAM, the ContosoMax Pro 5G delivers exceptional speed and responsiveness. Multitask with ease, run demanding apps, and enjoy a lag-free experience.\n\n### Pro-Grade Camera System\nCapture life's moments in extraordinary detail with the 64MP quad-camera system. Featuring a wide-angle lens, ultra-wide lens, macro lens, and depth sensor, this smartphone lets you take breathtaking photos and videos in any scenario. The 32MP front camera ensures you look your best in every selfie and video call.\n\n### Long-Lasting Battery\nStay powered throughout your day with the 4500mAh battery. Whether you're working, playing, or streaming, the ContosoMax Pro 5G provides hours of uninterrupted usage. Plus, with fast charging capabilities, you can quickly recharge and get back to what matters most.\n\n### Sleek Design\nThe ContosoMax Pro 5G is a true blend of form and function. Its sleek, ergonomic design fits comfortably in your hand, while the premium glass and metal finish exude sophistication and style. Choose from a range of stunning colors to match your personal aesthetic.\n\n### Advanced Security\nProtect your data with advanced security features including facial recognition and an in-display fingerprint sensor. Your information stays secure, and you can unlock your device with a simple glance or touch.\n\n## Specifications\n\n- **Display:** 6.7-inch Super AMOLED, Full HD+\n- **Processor:** Octa-core\n- **RAM:** 8GB\n- **Storage:** 128GB (expandable up to 1TB via microSD)\n- **Rear Camera:** 64MP (wide) + 12MP (ultra-wide) + 5MP (macro) + 5MP (depth)\n- **Front Camera:** 32MP\n- **Battery:** 4500mAh with fast charging\n- **Operating System:** Android 11\n- **Connectivity:** 5G, Wi-Fi 6, Bluetooth 5.2, NFC\n- **Security:** Facial recognition, In-display fingerprint sensor\n- **Colors Available:** Midnight Black, Glacial Blue, Sunrise Gold\n\n## Why Choose ContosoMax Pro 5G?\n\nAt Contoso Retail, we strive to bring you the latest and greatest in technology. The ContosoMax Pro 5G Smartphone stands out for its exceptional performance, stunning visuals, and advanced features. Perfect for anyone looking to upgrade their mobile experience, it is the ultimate choice for staying connected and productive in today's fast-paced world.\n\nVisit your nearest Contoso Retail store or shop online to get your hands on the ContosoMax Pro 5G Smartphone today. Elevate your mobile experience with ContosoMax Pro 5G – where innovation meets elegance.",
"Price": "$899.99"
}
```

![image](https://github.com/user-attachments/assets/ba359cd7-7a28-4c30-8662-e977a1704633)


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
  
4. Create a `.env` file (from sample.env) in the root directory and update <redacted> with  your Azure OpenAI credentials.
  
### Python Notebooks  
  
* Step 1: [Create Product Information (Textual Information)](https://github.com/liamca/gpt4-data-generator/blob/main/01-gpt4o-product-data-generator.ipynb)
* Step 2: [Create Product Images](https://github.com/liamca/gpt4-data-generator/blob/main/02-dalle-3-image-creation.ipynb)



