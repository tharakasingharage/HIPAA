# HIPAA Compliance Assessment System

A comprehensive, browser-based HIPAA compliance assessment and reporting system with real-time scoring, risk analysis, and PDF report generation.

![HIPAA Compliance](https://img.shields.io/badge/HIPAA-Compliance-teal)
![License](https://img.shields.io/badge/License-MIT-blue)

## Features

- **Six Safeguard Domains**: Complete assessment across Administrative, Physical, Technical Safeguards, Organizational Requirements, Policies & Procedures, and Documentation
- **Weighted Scoring**: Questions are weighted based on importance to provide accurate compliance scoring
- **Real-time Analysis**: Live compliance score updates as you answer questions
- **Risk Level Assessment**: Automatic risk level classification (Low, Medium, High, Critical)
- **PDF Report Generation**: Professional, downloadable compliance reports with detailed findings
- **Modern UI**: Beautiful, responsive interface with medical-themed design and smooth animations
- **No Dependencies Required**: Runs entirely in the browser using CDN-hosted libraries

## Technologies Used

- **Tailwind CSS** - Utility-first CSS framework
- **jsPDF** - PDF generation library
- **jsPDF-autoTable** - Table plugin for jsPDF
- **Google Fonts** - Outfit and JetBrains Mono fonts

## Usage

1. Open `index.html` in any modern web browser
2. Fill in your organization information:
   - Organization Name
   - Assessor Name
   - Assessment Date
   - Organization Type
3. Answer the compliance questions across all six domains:
   - **Administrative Safeguards** (25 questions)
   - **Physical Safeguards** (15 questions)
   - **Technical Safeguards** (18 questions)
   - **Organizational Requirements** (10 questions)
   - **Policies & Procedures** (12 questions)
   - **Documentation** (10 questions)
4. For each question, select one of:
   - ✅ Yes (Full compliance)
   - ⚠️ Partial (Partial compliance)
   - ❌ No (Non-compliant)
   - ➖ N/A (Not applicable)
5. View your real-time compliance score and risk level
6. Click "Generate PDF Report" to download a comprehensive compliance report

## Question Response Options

| Option | Color | Score Impact |
|--------|-------|--------------|
| Yes | Green | Full points |
| Partial | Amber | Partial points |
| No | Red | Zero points |
| N/A | Gray | Excluded from calculation |

## Risk Levels

- **Low** (80-100%): Strong compliance posture
- **Medium** (60-79%): Moderate gaps requiring attention
- **High** (40-59%): Significant compliance issues
- **Critical** (0-39%): Urgent remediation required

## PDF Report Includes

- Executive summary with overall compliance score
- Domain-by-domain breakdown with scores
- Detailed question responses
- Risk assessment
- Organization and assessor information
- Professional formatting suitable for stakeholders

## Screenshots

The application features:
- Dark medical-themed UI with teal accents
- Animated pulse line and floating orbs
- Interactive gauge displaying compliance score
- Tabbed navigation for different safeguard domains
- Responsive design for various screen sizes

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari

## File Structure

```
/workspace
├── index.html      # Main application (single-file SPA)
└── README.md       # This file
```

## Privacy & Security

- All data is stored locally in your browser session
- No data is sent to external servers
- PDF reports are generated client-side
- Clear assessment data by refreshing the page

## Disclaimer

This tool provides a self-assessment framework for HIPAA compliance but does not guarantee compliance. Consult with qualified legal and healthcare compliance professionals for official compliance verification.

## License

MIT License - Feel free to use and modify for your organization's needs.

---

Built with ❤️ for healthcare compliance professionals
