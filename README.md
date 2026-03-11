# CloudBase Agent Skills

A collection of AI agent skills for building full-stack applications with [Tencent CloudBase](https://cloudbase.net). This skill gives your coding agent deep knowledge of CloudBase APIs, authentication patterns, database operations, cloud functions, and more — so it can write correct, idiomatic CloudBase code without guessing.

## Installation

```bash
npx skills add TencentCloudBase/cloudbase-skills
```

Once installed, the skill is automatically applied when the agent detects relevant CloudBase tasks.

---

## Skill

### `cloudbase`

Comprehensive guidance for CloudBase development across Web, Mini Program, and Native App platforms. Covers:

- Platform detection and SDK selection
- Authentication flows per platform (Web, WeChat Mini Program, Node.js)
- Database operations — NoSQL and MySQL
- Cloud functions and CloudRun deployment
- Cloud storage
- AI model integration
- UI design guidelines
- Standard development workflow

---

## Recommended: CloudBase MCP

For the best experience, install the [CloudBase MCP](https://github.com/TencentCloudBase/cloudbase-mcp) server alongside this skill. MCP provides live tools for environment management, function deployment, database operations, and more.

```json
{
  "mcpServers": {
    "cloudbase": {
      "command": "npx",
      "args": ["@cloudbase/cloudbase-mcp@latest"]
    }
  }
}
```

**Config file locations by editor:**

| Editor | Location |
|---|---|
| Cursor | `.cursor/mcp.json` |
| Claude Code | `.mcp.json` |
| Windsurf | `~/.codeium/windsurf/mcp_config.json` |

---

## License

MIT
