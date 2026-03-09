You are a senior LaTeX engineer and resume designer.

Your task is to convert my existing CV (currently in PDF format) into a clean, professional LaTeX resume using the Harvard-style CV format.

Requirements:

1. Project Structure
Create a small LaTeX project with the following structure:

cv-harvard/
 ├── main.tex
 ├── sections/
 │    ├── summary.tex
 │    ├── education.tex
 │    ├── experience.tex
 │    ├── projects.tex
 │    ├── skills.tex
 │    └── certifications.tex
 └── output.pdf

2. LaTeX Design
- Use a Harvard-style resume layout (clean, academic, structured).
- One-page or maximum two-page layout.
- Use clear section titles.
- Ensure the PDF is ATS-friendly.
- Use modern fonts and proper spacing.

3. Sections to Implement

The CV must include these sections:

- Header (Name, Email, Phone, GitHub, LinkedIn)
- Professional Summary
- Education
- Work Experience
- Technical Projects
- Technical Skills
- Certifications or Achievements (optional)

4. Formatting Rules

- Use bullet points for achievements.
- Each experience should include:
  - Position
  - Company
  - Time period
  - Key responsibilities
  - Measurable achievements

Example format:

Software Engineer | Company Name
Jan 2023 – Present

• Built backend APIs using Spring Boot and PostgreSQL  
• Designed microservice architecture for scalable systems  
• Improved API response time by 40%

5. Technical Skills Layout

Group skills like:

Programming:
Java, TypeScript, Python

Backend:
Spring Boot, NestJS, Node.js

Frontend:
Next.js, React

Database:
PostgreSQL, MongoDB

DevOps:
Docker, GitHub Actions, Vercel, AWS

6. LaTeX Requirements

- Use pdflatex compatible packages
- Keep the code modular
- Avoid unnecessary packages
- Ensure clean compile with no warnings

7. Output

Generate:
1. A complete `main.tex`
2. All section `.tex` files
3. A clean Harvard-style layout
4. Ready-to-compile LaTeX project

After generating the structure, I will paste my CV content for you to convert into each section.