
# 📇 VCF Contact File Comparator

A Python-based tool to compare VCF (vCard) contact files exported from Google Contacts and Android devices.

## ✨ Features

- 📂 Compare multiple VCF contact files.
- 🔍 Identify differences between contact files.
- 👥 Find missing contacts.
- ♻️ Detect duplicate contacts.
- 📱 Compare Android contact backups.
- ☁️ Compare Google Contacts exports.
- 📊 Analyze contact information using Python.

## 📁 Project Structure

```text
root/
├── vcf/
│   ├── contacts_google.vcf
│   ├── contacts_android.vcf
│   └── contacts_backup.vcf
├── contacts.ipynb
└── README.md
```

## 📥 Input Files

- Place all `.vcf` contact files inside the inner `vcf/` folder.
- Export contacts from Google Contacts or your Android device.
- Copy the exported files into the `vcf/` folder.
- Add multiple VCF files for comparison.

## 🛠️ Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python libraries used in the notebook

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/imposter404/vcf.git
```

### 2. Navigate to the Project Directory

```bash
cd vcf
```

- Open `contacts.ipynb`.
- Place your VCF files inside the `vcf/` folder.
- Run the notebook cells in order.
- Review the comparison results.

## 🔒 Privacy and Security

- VCF files may contain personal contact information.
- Keep your contact files private.
- Do not upload personal contact files to a public GitHub repository.
- Add the following entry to `.gitignore` to prevent accidental uploads:

```gitignore
vcf/*.vcf
```

