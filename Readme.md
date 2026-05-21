# Trivey_Report_HTML_Template

A simple and customizable HTML template for generating Trivy vulnerability scan reports in a clean and readable format.

---

## Features

- Generate HTML vulnerability reports
- Easy to customize
- Simple and lightweight template
- Suitable for DevSecOps and CI/CD pipelines
- Displays vulnerabilities with severity levels

---

## Prerequisites

Make sure the following tools are installed:

- Docker
- Trivy

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Trivey_Report_HTML_Template.git
```

Move into the project directory:

```bash
cd Trivey_Report_HTML_Template
```

---

## Generate HTML Report

Run the following command:

```bash
trivy image --format template --template "@html.tpl" -o report.html <image-name>
```

### Example

```bash
trivy image --format template --template "@html.tpl" -o report.html nginx:latest
```

---

## Project Structure

```bash
Trivey_Report_HTML_Template/
│
├── html.tpl
├── report.html
└── README.md
```

---

## Output

The generated HTML report contains:

- Vulnerability ID
- Package Name
- Installed Version
- Fixed Version
- Severity
- Description

---

## Technologies Used

- HTML
- CSS
- Trivy

---

## Use Cases

- Container Image Security Scanning
- DevSecOps Projects
- CI/CD Security Integration
- Vulnerability Monitoring

---

## License

This project is licensed under the MIT License.

---

## Author

Shakthivel K