# DICOM A to Z: Learning Modules with Python

Welcome to the DICOM A to Z repository! This project is designed as a learning resource for working with DICOM (Digital Imaging and Communications in Medicine) files using Python. The goal is to provide interactive, hands-on modules that guide learners from the basics through advanced topics in medical image processing.

## Project Structure

- `notebooks/` - Jupyter notebooks containing learning modules and exercises.
- `scripts/` - Python scripts for reusable code and utilities.
- `data/` - Directory for sample DICOM files (see below for details).
- `requirements.txt` - List of required Python packages.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hrishi2893/dicom-a-to-z.git
   cd dicom-a-to-z
   ```

2. **Create and activate a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Then open the notebooks from the `notebooks/` folder.

## Sample Data

- Place sample DICOM files in the `data/` directory.
- If you do not have DICOM files, see `data/README.md` for sources and instructions.

## Learning Modules

Check the `notebooks/` directory for available modules. Start with `intro_to_dicom.ipynb`.

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or new modules.

## License

This project is licensed under the MIT License.