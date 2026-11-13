# AI Workflow Kit

Local tools for working with file-capable AI agents. Compare and refine designs, or keep project state in a memory workspace.

## Choose a package

| Package | Use | Version |
|---|---|---|
| [Design Lab](packages/design-lab/README.md) | Adjust a live component or page, test edge cases, save selections, and continue reviews | 1.5.2 beta |
| [Memory System Starter Kit](packages/memory-system-starter-kit/README.md) | Create a local workspace for rules, memory, and resumable project records | 1.0.0 beta |

Each package has its own quick start. Keep its required files together. No package uploads user content or configures a remote repository during normal setup.

## Start

For Design Lab, open its folder in a file-capable agent and follow its installation prompt. Keep the design-lab and variant-lab skill folders beside each other. Open the included example to inspect the panel.

For Memory Kit, run its setup helper with a new destination, then open the created workspace in your agent. Existing destinations are refused. Global client changes are optional and separate.

Design Lab's browser demo needs no Node installation. Optional command-line tests require Node 20 or newer. Memory setup requires Python 3.9 or newer; its health and dashboard scripts need Bash. Git is optional.

## Beta scope

The packages were checked on macOS. Design Lab includes state/browser tests and an agent-generated component pilot. Memory Kit includes a synthetic new-owner setup and saved-record resume pilot. These checks are not a real-user study or proof of automatic loading in every client. Other operating systems and virtual-keyboard behavior remain unverified.

Keep private records and credentials out of shared payloads. Review content before backup, sync, or publication. Follow the data policy for your device, organization, and AI tool.

## Maintainer and license

Maintained by Pei Shi Hu. These two packages use the [MIT License](LICENSE). Required notices must remain when you redistribute covered material. See each package changelog for its changes.
