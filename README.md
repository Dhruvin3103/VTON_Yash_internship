# VTON_Yash_internship
### 1. Create and Activate Virtual Environment
# Create virtual environment
```python
python -m venv venv
```

# Activate virtual environment
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
### 2. Install Requirements

Before running the application, make sure to install the required dependencies by executing the following command:

```bash
pip install -r requirements.txt
```


### 3. Add Environment Variables

To configure your environment variables, follow these steps:

1. Create a `.env` file in the root directory of your project.

2. Open the `.env` file in a text editor and add the following variables:

```plaintext
CLOUD_NAME=your_cloud_name
API_KEY=your_api_key
API_SECRET=your_api_secret
REPLICATE_API_TOKEN=your_replicate_api_token
