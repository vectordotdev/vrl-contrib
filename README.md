# VRL Contrib

> [!WARNING]  
> This repository is new and experimental.

A community-driven repository of [Vector Remap Language (VRL)](https://vector.dev/docs/reference/vrl/) programs and examples for transforming, normalizing, and enriching observability data.

**Note:** VRL programs in this repository are community-contributed and not officially supported by DataDog maintainers. 
Always test programs in a non-production environment first.

## Overview

**VRL Contrib** is a central hub for sharing VRL programs that help you:

- **Transform logs** into standard formats like [OCSF](https://github.com/ocsf), [ECS](https://www.elastic.co/guide/en/ecs/current/index.html), and more
- **Normalize data** from various sources (cloud providers, security tools, applications)
- **Enrich events** with contextual information
- **Parse and structure** unstructured log data
- **Learn VRL** through real-world examples

## Repository Structure

```
vrl-contrib/
├── programs/          # Complete VRL programs
│   ├── aws/           # AWS service log transformations
│   ├── kubernetes/    # Kubernetes log parsing
│   ├── security/      # Security tool integrations
│   └── ...
├── examples/          # Learning examples and tutorials
```

## Documentation

- **[Vector Documentation](https://vector.dev/docs/)** - Official Vector docs
- **[VRL Reference](https://vector.dev/docs/reference/vrl/)** - VRL language reference
- **[VRL Functions](https://vector.dev/docs/reference/vrl/functions/)** - Built-in VRL functions
- **[VRL Playground](https://playground.vrl.dev/)** - Test VRL online

## Contributing

We welcome contributions from everyone! Here's how you can help:

### Ways to Contribute

- **Add new VRL programs** for data sources not yet covered
- **Improve existing programs** with better performance or features
- **Submit examples** that help others learn VRL
- **Report issues** or suggest improvements
- **Review pull requests** from other contributors

### Contribution Process

1. **Fork** this repository
2. **Create a branch** for your contribution
   ```bash
   git checkout -b my-awesome-vrl-example
   ```
3. **Add your VRL program** in the appropriate directory
4. **Include tests and examples** showing input/output
5. **Submit a pull request** with a clear description

## 💡 Example Use Cases

- Converting vendor-specific logs to open standards (OCSF, ECS)
- Normalizing multi-cloud logs into a unified schema
- Enriching security events with threat intelligence
- Parsing and structuring unstructured application logs
- Extracting metrics from log data
- Redacting sensitive information (PII, credentials)
