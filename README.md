# Fabricio Andreis Scoop Bucket

This is a [Scoop](https://scoop.sh/) bucket for packages maintained by [@fabricioandreis](https://github.com/fabricioandreis).

## 📦 Available Packages

- **mcp-emailemnuvem** - Email em Nuvem MCP Server - Model Context Protocol server for Email em Nuvem API

## 🚀 Installation

### 1. Add this bucket to Scoop

```powershell
scoop bucket add fabricioandreis https://github.com/fabricioandreis/scoop-bucket
```

### 2. Install packages

```powershell
# Install mcp-emailemnuvem
scoop install mcp-emailemnuvem
```

### 3. Update packages

```powershell
# Update all packages
scoop update *

# Update specific package
scoop update mcp-emailemnuvem
```

## 📋 Package List

| Package | Description | Homepage |
|---------|-------------|----------|
| mcp-emailemnuvem | Email em Nuvem MCP Server | [GitHub](https://github.com/fabricioandreis/mcp-emailemnuvem) |

## 🔧 Configuration

After installing `mcp-emailemnuvem`, you'll need to set up your environment variables:

```powershell
# Set required environment variables
$env:EMAILEMNUVEM_JWT_SECRET = "your-jwt-secret"
$env:EMAILEMNUVEM_API_BASE_URL = "https://api.emailemnuvem.com.br/v1/"

# Run the server
mcp-emailemnuvem
```

## 🐛 Issues

If you encounter any issues with the packages in this bucket, please:

1. Check if the issue is with the package itself by visiting the project's GitHub repository
2. If it's a packaging issue, create an issue in this repository
3. For application issues, create an issue in the respective project repository

## 📚 About Scoop

[Scoop](https://scoop.sh/) is a command-line installer for Windows that makes it easy to install and manage software packages.

## 🤝 Contributing

This bucket is automatically maintained by GoReleaser. Package manifests are generated and updated automatically when new releases are published.

---

**Maintained by**: [@fabricioandreis](https://github.com/fabricioandreis)
