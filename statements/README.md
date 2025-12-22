# Financial Statements Folder

Place your financial statement PDF files in this folder.

## File Naming Convention

The HTML page expects files to be named:
- `financial-statement-2023.pdf` for the 2023 statement
- `financial-statement-2024.pdf` for the 2024 statement
- `financial-statement-YYYY.pdf` for other years (replace YYYY with the year)

## Adding New Statements

1. Add your PDF file to this folder with the appropriate name
2. Edit `financial-statements.html` to add a new statement card following the existing pattern
3. Update the file path in the download link to match your file name

## Example

If you have a statement for 2025:
1. Save it as `financial-statement-2025.pdf` in this folder
2. Add a new statement card in `financial-statements.html`:

```html
<div class="statement-card">
    <div class="statement-icon">📄</div>
    <h3>Financial Statement 2025</h3>
    <p class="statement-date">Year: 2025</p>
    <p class="statement-description">Annual financial statement for the fiscal year 2025</p>
    <a href="statements/financial-statement-2025.pdf" class="btn btn-primary" download>
        <span>📥</span> Download PDF
    </a>
</div>
```

