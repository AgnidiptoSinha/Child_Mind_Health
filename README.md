# Child Mind Health ML Project

This project focuses on analyzing and predicting child mental health outcomes using machine learning techniques.

## Project Structure

```
├── .ipynb_checkpoints/
├── Child_Mind_Health.ipynb     # Main analysis notebook
├── data_dictionary.csv        # Feature descriptions
├── train.csv                  # Training dataset
├── test.csv                   # Test dataset
├── series_train.parquet/       # Training parquet files (Accelerometer data)
├── series_test.parquet/        # Testing parquet files (Accelerometer data)
├── avg_parquet.csv            # Preprocessed data
├── requirements.txt           # Python dependencies
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- git

### Setup Instructions

1. Clone the repository
   ```bash
   git clone [repository-url]
   cd [project-directory]
   ```

2. Install required packages
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project

1. Start Jupyter Notebook
   ```bash
   jupyter notebook
   ```

2. Open the notebooks in the following order:
   - `Preparing_Data.ipynb` - Data preprocessing and cleaning
   - `Child_Mind_Health.ipynb` - Main analysis and modeling

## Data Files

- `train.csv`: Training dataset
- `test.csv`: Test dataset for predictions
- `data_dictionary.csv`: Description of all features
- `avg_parquet.csv`: Preprocessed data file

## Notes

- Required Python packages are listed in `requirements.txt`
- Data preprocessing steps are documented in `Preparing_Data.ipynb`
- Model development and analysis can be found in `Child_Mind_Health.ipynb`

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Submit a pull request
