# 📥 ImmutableHub Pull Architecture

---


# [After Login and Project setup is already done shown here https://github.com/immutablehub/immutablehub_commits_architecture/blob/main/workflow.md?plain=1]

## Pull Mechanism

> All pulls on immutablehub are natively Git-powered. The system retrieves data from the network via Git bundles and integrates them using a merge strategy. This ensures that the transition from the decentralized network to your local machine is seamless and preserves the original state.

## Bash
Pull commited updates to a local repo  setup
```bash
ihub op pull <reponame>
```
Pull commited updates to a local mcp repo  setup
```bash
ihub op pull <mcpreponame> --mcp true
```
Pull commited updates to a local prompt data  setup
```bash
ihub op pull <projectname> --prompt true
```

