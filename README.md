# asdf-q


This plugin allows you to easily install and manage multiple versions of the Amazon Q CLI using [asdf](https://asdf-vm.com/) or [mise](https://mise.jdx.dev/).

---

## 📦 Installation

```bash
# Add the plugin
mise plugins install q https://github.com/cloudhivemind/asdf-q.git
```

## 🔍 List Available Versions

```bash
mise ls-remote q
```

## 🚀 Install a Specific Version

```bash
# Install the latest version
mise install q@latest

# Or install a specific version
mise install q@1.19.3
```

## ✅ Verify Installation

```bash
q --version
```

