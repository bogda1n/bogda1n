```typescript
class Bogdan {
    role: string;
    skills: string[];
    projects: Record<string, string>;
    socials: Record<string, string>;

    constructor() {
        this.role = "Freelance Web Developer | QA Analyst";
        this.skills = [
            "Frontend: HTML, CSS, JavaScript, TypeScript, React, Vue",
            "Backend: Node.js, Express, C# (.NET), Python (FastAPI, Flask)",
            "Databases: MongoDB, NoSQL, PostgreSQL, MySQL",
            "Testing: Selenium, Playwright, Jest, Cypress",
            "DevOps: Docker, CI/CD, Git, AWS, Firebase",
            "Other: SaaS Development, OCR (Tesseract), PyQt"
        ];
        this.projects = {
            "Session-Based Test Management Platform": "Streamlining QA workflows",     
            "Full-Stack SaaS App": "Coming soon...",
            "Freelance Web Projects": "Building modern web applications and web sites"
        };
        this.socials = {
            "GitHub": "https://github.com/bogda1n",
            "LinkedIn": "https://www.linkedin.com/in/bogdan-dincă",
        };
    }

    connect(): Record<string, string> {
        return this.socials;
    }

    workOn(): Record<string, string> {
        return this.projects;
    }
}

