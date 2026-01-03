# Welcome to MCP-Atlassian

This repository is designed to provide seamless integration between the Atlassian suite (Jira, Confluence, etc.) and Supabase. Our goal is to streamline your workflow by combining the project management capabilities of Atlassian tools with the robust backend solutions offered by Supabase.

## Key Features
- Simplified API communication between Supabase and Atlassian tools.
- Ready-to-use scripts and configurations.
- Detailed examples to get you started quickly.

## Getting Started

### Prerequisites
Before integrating this repo into your workflow, ensure the following:
- You have a [Supabase](https://supabase.com/) Cloud account.
- Your Atlassian tools are set up and ready to be extended (e.g., Jira workflows, Confluence spaces).
- Node.js and npm are installed on your local machine.

### Installation and Configuration
1. Clone this repository:
   ```bash
   git clone https://github.com/rubbers5018/mcp-atlassian.git
   ```

2. Navigate to the directory:
   ```bash
   cd mcp-atlassian
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file:
   ```bash
   touch .env
   ```

5. Populate the `.env` file with your Supabase and Atlassian credentials. Below is an example:
   ```env
   SUPABASE_URL=your-supabase-url
   SUPABASE_KEY=your-supabase-key
   ATLASSIAN_API_TOKEN=your-atlassian-api-token
   ```

6. Test the integration:
   ```bash
   npm run test
   ```

### Usage
- Run the application:
  ```bash
  npm start
  ```
- Check the logs to ensure proper connection between Atlassian tools and Supabase.

## Support
If you encounter issues, please open an [issue](https://github.com/rubbers5018/mcp-atlassian/issues) in the repo.

## License
This project is licensed under the [MIT License](LICENSE).