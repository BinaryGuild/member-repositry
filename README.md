# member-repositry

A repository where students submit a pull request to add themselves to `members.json`. This is how they formally join the BinaryGuild community.

## Getting Started

To add yourself to the members list:

1. Read the [CONTRIBUTING.md](./CONTRIBUTING.md) file for detailed instructions
2. Fork this repository
3. Add your information to `members.json` in the specified format
4. Submit a pull request

**Note:** Once your PR is merged and your information is added to `members.json`, you will automatically be added to the BinaryGuild `contributors` GitHub team.

## Project Structure

- `members.json` - The main file containing all member information
- `CONTRIBUTING.md` - Guidelines for submitting a PR to join
- `README.md` - This file
- `.github/workflows/add-members-to-team.yml` - Automated workflow to add members to the contributors team

## Format

Each member entry in `members.json` should follow this format:

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

For more details, see [CONTRIBUTING.md](./CONTRIBUTING.md)

## Automation

Once you join by having your information merged into `members.json`, the following happens automatically:

- A GitHub Actions workflow runs to read your GitHub username from `members.json`
- You are automatically added to the BinaryGuild `contributors` team
- This gives you membership in the organization's contributor team

**Requirements:** The workflow requires the following permissions to be enabled in the repository:
- Read access to repository contents
- Write access to organization members
