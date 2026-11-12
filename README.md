# SPS Core Compat

SPS is Redon's local-first Desktop workspace. SPS Core Compat is a Paperclip compatibility mirror used to inspect and exercise upstream-derived behavior; it is not the Core runtime used by SPS Desktop and does not define SPS product features or releases.

## How it relates to SPS

The SPS product runtime is maintained in [SPS Core](https://github.com/Powerpunch777/SPS-Core), and the Desktop application is maintained in [SPS Source](https://github.com/Powerpunch777/SPS-Source). This mirror exists so compatibility code and upstream provenance can be reviewed separately while SPS-owned contracts evolve.

Code and documentation in this repository may describe Paperclip-specific company, task, agent, or UI behavior. Those descriptions apply to the compatibility project; they are not promises about SPS workspaces or supported product workflows.

## Upstream project

- [Paperclip source](https://github.com/paperclipai/paperclip)
- [Paperclip documentation](https://docs.paperclip.ing)
- [License](LICENSE) and upstream notices in this repository

Use the package scripts and development setup shipped with the mirrored source. Preserve upstream attribution and license terms. Changes here do not qualify an SPS Desktop release; use the SPS product repositories and their candidate support matrix for product work.
