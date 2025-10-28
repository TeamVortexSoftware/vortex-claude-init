# @teamvortexsoftware/vortex-claude

> Add Vortex AI integration to your project for Claude Code

## One-Line Setup

```bash
npx @teamvortexsoftware/vortex-claude init
```

You'll be prompted for:
- Your Vortex API key
- Your widget ID

That's it! This adds AI-powered Vortex integration to your project with your credentials baked in.

## What It Does

Adds a `/integrate-vortex` slash command to VS Code with Claude Code that:
- Analyzes your codebase (framework, auth, grouping mechanism)
- Chooses the right Vortex SDK and components
- Generates all integration code
- Implements JWT endpoints
- Adds UI components
- Creates landing pages
- Configures everything

## How to Use

1. **Get your credentials**:
   - [API key](https://admin.vortexsoftware.com/members/api-keys)
   - [Widget ID](https://admin.vortexsoftware.com) (create a widget first)

2. **Run init** (one time):
   ```bash
   npx @teamvortexsoftware/vortex-claude init
   ```
   Enter your API key and widget ID when prompted.

3. **Reload VS Code**:
   - Cmd/Ctrl + Shift + P → "Reload Window"

4. **Integrate Vortex**:
   - Type: `/integrate-vortex`
   - Claude analyzes your codebase and implements everything
   - Your credentials are already configured!

5. **Done!**
   - Full Vortex integration in ~30 minutes
   - Review and test the code

## Requirements

- VS Code with [Claude Code extension](https://claude.com/claude-code)
- [Vortex API key](https://admin.vortexsoftware.com/members/api-keys)
- [Vortex widget](https://admin.vortexsoftware.com)

## Supported Tech Stacks

**Frontend:**
- React, Next.js
- React Native
- Angular (14, 19, 20)
- Vue (coming soon)

**Backend:**
- Node.js (Express, Fastify)
- Next.js App Router
- Python (Flask, Django)
- Ruby (Rails)
- Java (Spring Boot)
- Go, C#, PHP, Rust

## Example

```bash
# Initialize Vortex AI integration
npx @teamvortexsoftware/vortex-claude init

# You'll see:
🚀 Setting up Vortex AI integration for Claude Code...

First, we need your Vortex credentials:

Vortex API Key (from https://admin.vortexsoftware.com/members/api-keys): vortex_xxxxx
Widget ID (from https://admin.vortexsoftware.com): widget_yyyyy

✅ Credentials received
✅ Created .claude/commands/integrate-vortex.md
✅ Added VORTEX_API_KEY to .env.local

🎉 Setup complete!

# Reload VS Code, then type:
/integrate-vortex

# Claude uses your credentials and implements everything!
```

## What Gets Implemented

✅ Backend JWT generation endpoint
✅ API routes for invitations
✅ Frontend component integration
✅ Landing page for invitation acceptance
✅ Database membership creation
✅ Environment variables
✅ Widget configuration guide

## Time to Integration

- **With AI**: ~30 minutes
- **Manual**: 4-6 hours

## Support

- [Documentation](https://docs.vortexsoftware.com)
- [Admin Panel](https://admin.vortexsoftware.com)
- [GitHub Issues](https://github.com/TeamVortexSoftware/vortex-suite/issues)

## License

Apache-2.0
