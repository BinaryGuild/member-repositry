# Contributing to Member Repository

Welcome to the member repository! Follow these steps to add yourself to the community:

## How to Join

1. **Fork the repository**
   - Click the "Fork" button at the top right of this repository

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/member-repositry.git
   cd member-repositry
   ```

3. **Create a new branch**
   ```bash
   git checkout -b add/your-name
   ```

4. **Add yourself to members.json**
   - Open `members.json`
   - Add your information following this format:
   ```json
   {
     "name": "Your Name",
     "github": "yourusername",
     "role": "contributor",
     "skills": ["JavaScript", "Python"],
     "student_at": "XYZ University",
     "joined": "2025-01"
   }
   ```

5. **Commit your changes**
   ```bash
   git add members.json
   git commit -m "Add <Your Name> to members list"
   ```

6. **Push to your fork**
   ```bash
   git push origin add/your-name
   ```

7. **Create a Pull Request**
   - Go to the original repository
   - Click "Pull Request" and select your branch
   - Provide a brief description and submit!

## Member Schema

| Field | Type | Description | Required |
|-------|------|-------------|----------|
| name | string | Your full name | Yes |
| github | string | Your GitHub username | Yes |
| role | string | Your role (e.g., "contributor", "maintainer") | Yes |
| skills | array | List of your technical skills | No |
| student_at | string | University or organization you study/work at | No |
| joined | string | Date you joined (YYYY-MM format) | Yes |

## Example

```json
[
  {
    "name": "Alice Johnson",
    "github": "alicejohn",
    "role": "contributor",
    "skills": ["JavaScript", "React", "Python"],
    "student_at": "MIT",
    "joined": "2025-01"
  },
  {
    "name": "Bob Smith",
    "github": "bobsmith",
    "role": "maintainer",
    "skills": ["Go", "Docker", "Kubernetes"],
    "student_at": "Stanford University",
    "joined": "2024-12"
  }
]
```

## Guidelines

- Keep entries in alphabetical order by name
- Use valid JSON format
- Ensure all required fields are filled
- One PR per person
- Be respectful and inclusive!

## Questions?

If you have any questions, feel free to open an issue or reach out to the maintainers.

Happy joining! 🎉
