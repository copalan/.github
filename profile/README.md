## Hi there 👋

Copalan is an AI-assisted knowledge platform designed to curate and improve your organisation's internal knowledge base, regardless of where that knowledge lives. We connect to various third-party platforms—GitHub, Atlassian Confluence, Google Drive, Slack, and Jira—to index, analyse, and enhance documentation quality using AI.

Our mission is to help organisations maintain high-quality curated documentation by automatically identifying gaps, monitoring support conversations, generating actionable recommendations and always keeping human contributors in the loop for regular reviews. We believe that good documentation is the foundation of effective teams, and we're building the tools to make maintaining it effortless.

## 🌈 Contribution Guidelines

We welcome contributions from the community! Here's how you can get involved:

### Getting Started

1. **Fork and clone** the repository
2. **Set up your development environment** following our [CONTRIBUTING.md](docs/guidance/CONTRIBUTING.md)
3. **Read the architecture docs** in `docs/guidance/` to understand our patterns
4. **Pick an issue** or propose a new feature

### Prerequisites

- **[mise](https://mise.jdx.dev/)** for tool version management
- **[Docker](https://docs.docker.com/get-docker/)** for the PostgreSQL database
- **[overmind](https://github.com/DarthSim/overmind)** for process management

### Development Workflow

```bash
# Install dependencies and configure
mise install
mise configure

# Start development servers
mise dev
```

Access the application at:
- Frontend: http://localhost:5173
- Backend API: http://localhost:8080

### Code Standards

- **Language**: Use British English in documentation (e.g., "organise" not "organize")
- **Formatting**: Run `mise lint-backend` for Go code before committing
- **Testing**: Run `mise test` to ensure all tests pass
- **Architecture**: Follow our domain-driven design patterns documented in `docs/guidance/`
- **Commits**: Keep them focused and atomic

### What We Need Help With

- **Backend**: Go development with clean architecture patterns
- **Frontend**: React/TypeScript with TanStack Query and shadcn/ui
- **Integrations**: Enhancing connections to knowledge platforms
- **AI/ML**: Improving documentation analysis and recommendations
- **Documentation**: Making our guides clearer and more comprehensive

## 👩‍💻 Useful Resources

### Documentation

- **[README.md](README.md)** - Project overview and quick start
- **[CONTRIBUTING.md](docs/guidance/CONTRIBUTING.md)** - Detailed setup and development guide
- **[Backend Architecture](docs/guidance/tech/backend.md)** - Go backend patterns and structure
- **[Frontend Architecture](docs/guidance/tech/frontend.md)** - React frontend patterns
- **[Project Structure](docs/guidance/structure.md)** - How the codebase is organised

### Key Technologies

**Backend:**
- Go 1.24.6 with clean architecture
- PostgreSQL with River for job queuing
- Event-driven architecture with pgq
- Domain-driven design with CQRS

**Frontend:**
- React with TypeScript
- TanStack Query for server state
- shadcn/ui component library
- Vite for build tooling

**Integrations:**
- Anthropic Claude for AI analysis
- GitHub, Google, Confluence, Slack, Jira APIs

### Community Resources

- **Issues**: Report bugs or request features on [GitHub Issues](https://github.com/copalan/copalan/issues)
- **Discussions**: Join conversations about architecture and features
- **License**: Non-Commercial Share-Alike (see [LICENSE](LICENSE))

### Important Notes

- This project uses a **non-commercial license** - internal business use is permitted, but you cannot use it to build commercial products or services
- For commercial licensing enquiries, contact the copyright holder
- All contributions must be shared under the same license

## 🍿 Fun Facts

- Our team runs on **proper British tea** ☕ (no coffee debates here, though Earl Grey vs. English Breakfast is fair game)
- We're fans of **domain-driven design** because naming things correctly is half the battle

### Tech Stack Breakfast Order

If our tech stack were breakfast items:
- **Go**: The reliable full English - solid, dependable, gets the job done
- **React**: Fresh avocado toast - modern, popular, sometimes controversial
- **PostgreSQL**: Classic porridge - been around forever, never lets you down
- **Anthropic Claude**: The AI-powered smoothie - sophisticated and surprisingly intelligent
- **mise**: The perfectly timed coffee delivery - manages everything just when you need it

---

**Ready to contribute?** Check out our [CONTRIBUTING.md](docs/guidance/CONTRIBUTING.md) and dive in! We're excited to see what you'll build with us. 🚀
