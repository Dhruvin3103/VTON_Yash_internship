# VTON_Yash_internship

# State Of The Art Virtual Try-On (SOTA VTON)

This repository contains a Streamlit application that allows users to perform virtual try-on of garments on model images. Additionally, it provides a garment search feature that scrapes data from various e-commerce websites such as Bewakoof, Amazon, and Ajio. The application also generates a GIF showcasing the output image from different angles using a multi-view diffusion model.

## Features

1. **Virtual Try-On (VTON)**: Users can upload a garment image and a model image, and the application will generate an output image with the garment virtually tried on the model.
2. **Garment Search**: Users can search for garments on Bewakoof, Amazon, or Ajio by entering a search query. The application scrapes the websites and displays the results, allowing users to select a garment and try it on.
3. **Multi-View Diffusion**: The application generates a GIF showcasing the output image from different angles using a multi-view diffusion model.

## Installation

1. Clone the repository:

## 1. Create and Activate Virtual Environment
### Create virtual environment
```python
python -m venv venv
```

### Activate virtual environment
#### Windows
```cmd
venv\Scripts\activate
```

#### macOS/Linux
```bash
source venv/bin/activate
```

## 2. Install Requirements

Before running the application, make sure to install the required dependencies by executing the following command:

```bash
pip install -r requirements.txt
```


## 3. Add Environment Variables

To configure your environment variables, follow these steps:

1. Create a `.env` file in the root directory of your project.

2. Open the `.env` file in a text editor and add the following variables:

```plaintext
CLOUD_NAME=your_cloud_name
API_KEY=your_api_key
API_SECRET=your_api_secret
REPLICATE_API_TOKEN=your_replicate_api_token
```

## 4. Install Chrome WebDriver (For Linux/Mac)

If you're using Linux or macOS, you'll need to install Chrome WebDriver. Follow these steps:

1. Download Chrome WebDriver from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads).

2. Follow the installation instructions provided for your operating system.

Chrome WebDriver is required for web scraping functionalities in the project. Ensure you download the appropriate version compatible with your Chrome browser version.

## 5. Run the Application

To run the application, follow these steps:

1. Navigate to the `code` directory in your terminal.

2. Run the following command:

```python
streamlit run app.py
```

## Usage

1. Open the Streamlit application in your web browser.
2. Navigate to the "VTON" tab to perform virtual try-on.
- Upload a garment image and a model image using the respective file uploaders.
- Select the category (upper_body, lower_body, or dresses) for the garment.
- Optionally, provide a garment description.
- Click the "Run" button to generate the output image.
3. Navigate to the "Garment Search" tab to search for garments.
- Enter a search query and select the desired website (Bewakoof, Amazon, or Ajio).
- Click the "Search" button to retrieve the search results.
- Click the "Try on" button next to a garment to try it on the model.
4. Navigate to the "Multi-View" tab to generate a GIF showcasing the output image from different angles.
- The GIF will be automatically generated if an output image is available from the "VTON" tab.

## Dependencies

The main dependencies used in this project are:

- Streamlit
- Replicate/HuggingFace
- Cloudinary
- Selenium
- BeautifulSoup


Please refer to the `requirements.txt` file for the complete list of dependencies and their versions.

## Comparison between various models
![image](https://github.com/Dhruvin3103/VTON_Yash_internship/assets/114014218/7bd17810-46fd-4062-9e28-170f7e8a2386)
![image](https://github.com/Dhruvin3103/VTON_Yash_internship/assets/114014218/18eb1f85-a91c-4b88-b179-14546dfd21bb)

## Screeshots
- Inital page
![image](https://github.com/Dhruvin3103/VTON_Yash_internship/assets/114014218/0bde0076-2811-48dc-89eb-7b1a6a01d9bf)
- vton tab
  ![image](https://github.com/Dhruvin3103/VTON_Yash_internship/assets/114014218/43a3617e-6cb7-4c31-a7f2-17fb66744115)
  ![image](https://github.com/Dhruvin3103/VTON_Yash_internship/assets/114014218/c9902efb-54ec-46cc-947e-2bd24e8ae7d8)
- Search tab
  ![image](https://github.com/Dhruvin3103/VTON_Yash_internship/assets/114014218/3edc8b33-f4e6-4fb4-8c98-e3af8c2aa0aa)

- sample multiview gifs
  ![image](https://github.com/Dhruvin3103/VTON_Yash_internship/blob/main/assests/Virtual%20Try%20on%20(2).svg)

## ppt/yt links 
- https://docs.google.com/presentation/d/1LKf05Ficx8ONUmSbpfWhh17VmTftko__SLp1JVyyvw8/edit?usp=sharing
- https://www.youtube.com/watch?v=zXVoXbgFv14
- https://www.youtube.com/watch?v=XVMih_UxdB0
