# Dataset Generator Project
This project is a dataset generator that utilizes the OpenAI API and additional libraries for handling asynchronous tasks, environment variables, and progress tracking. The generator can be customized to create datasets for machine learning tasks, using various APIs or random sampling techniques.

## Project Overview
This Jupyter notebook is designed to:

- Generate datasets using API queries.
- Utilize the OpenAI API to generate synthetic data samples.
- Manage environment variables for secure API usage.
- Track progress of dataset generation using a progress bar.
## Requirements
This project requires the following Python libraries:

- asyncio: For handling asynchronous API requests.
- dotenv: To manage environment variables (like API keys).
- openai: To interact with the OpenAI API for generating synthetic data.
- os: For file and environment variable management.
- random: For generating random samples.
- tqdm: For tracking progress with progress bars.
- yaml: For configuration file handling.
## Setup
1. Clone the repository to your local machine:

```bash
git clone https://github.com/imeeeeeeee/dataset-generator-setup.git
```
2. Navigate to the project directory:

```bash
cd dataset-generator-setup
```
3. Install the required libraries:

```bash
pip install -r requirements.txt
```
4. Create a `.env` file in the root directory and add your OpenAI API key:

```bash
OPENAI_API_KEY=your-api-key-here
```
Usage
Open the Jupyter notebook (Dataset_generator.ipynb) and follow the instructions within to generate your dataset. You can customize the dataset generation parameters as needed, including API queries and sampling methods.

Run the notebook either locally or in a cloud-based Jupyter environment (e.g., Google Colab).



