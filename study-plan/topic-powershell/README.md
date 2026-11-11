# PowerShell for DevOps and Azure Automation

This study plan teaches PowerShell as a practical DevOps automation language: command discovery, pipeline use, scripting, reusable functions, modules, testing, Azure automation, and CI/CD integration.

## Prerequisites

- PowerShell 7+ installed, or Windows PowerShell available on the machine
- Python 3.10+ and Jupyter Notebook or JupyterLab
- Visual Studio Code recommended
- Basic command-line familiarity
- Optional but strongly recommended: an Azure subscription for the cloud lessons
- Optional: GitHub account for the CI/CD lesson and capstone workflow

## Recommended Resources

### Bookmark These First
- [PowerShell Documentation](https://learn.microsoft.com/en-us/powershell/) — Official reference for all cmdlets and concepts
- [Azure PowerShell overview](https://learn.microsoft.com/en-us/powershell/azure/overview) — Cloud automation with PowerShell
- [Microsoft Learn: Automate Administration with PowerShell (AZ-040T00)](https://learn.microsoft.com/en-us/training/courses/az-040t00) — Official Microsoft training aligned with this plan
- [PowerShell Gallery](https://www.powershellgallery.com/) — Community modules and scripts repository

### Additional Resources
- [Install PowerShell on Windows](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows)
- [PowerShell on GitHub](https://github.com/PowerShell/PowerShell)
- [PowerShell Team Blog](https://devblogs.microsoft.com/powershell/)
- [PowerShell for DevOps: Managing Cloud Resources and Automating CI/CD Processes](https://medium.com/@genai.lumenex/powershell-for-devops-managing-cloud-resources-and-automating-ci-cd-processes-78ddf367278d)

## Study Plan Overview

| Phase | Focus | Lessons |
| --- | --- | --- |
| Phase 1 | Foundations | [1.1](phase-1-foundations/lesson-1.1-installation-first-commands.ipynb), [1.2](phase-1-foundations/lesson-1.2-objects-pipeline.ipynb), [1.3](phase-1-foundations/lesson-1.3-variables-collections-providers.ipynb) |
| Phase 2 | Scripting Mechanics | [2.1](phase-2-scripting-mechanics/lesson-2.1-control-flow-iteration.ipynb), [2.2](phase-2-scripting-mechanics/lesson-2.2-functions-advanced-parameters.ipynb), [2.3](phase-2-scripting-mechanics/lesson-2.3-errors-formatting-json.ipynb) |
| Phase 3 | Modules and Automation | [3.1](phase-3-modules-automation/lesson-3.1-modules-gallery.ipynb), [3.2](phase-3-modules-automation/lesson-3.2-jobs-runbooks.ipynb), [3.3](phase-3-modules-automation/lesson-3.3-testing-quality.ipynb) |
| Phase 4 | Cloud and DevOps | [4.1](phase-4-cloud-devops/lesson-4.1-azure-auth-context.ipynb), [4.2](phase-4-cloud-devops/lesson-4.2-resource-provisioning-automation.ipynb), [4.3](phase-4-cloud-devops/lesson-4.3-ci-cd-secrets.ipynb) |
| Capstone | End-to-end automation toolkit | [Capstone](capstone/capstone-project.ipynb) |

## Time Estimate

- Lessons: 12 total
- Typical lesson time: 20-40 minutes each
- Estimated total time: about 8-12 hours
- Capstone: 2-4 hours

## Capstone Overview

You will build a PowerShell automation toolkit for a DevOps team. The final result combines reusable functions, local validation, Azure resource automation, secret handling, and a CI/CD workflow that runs the scripts and tests.

## How to Use the Notebooks

1. Install Jupyter with `pip install notebook` or `pip install jupyterlab`.
2. Open the notebooks from the `study-plan/topic-powershell/` directory.
3. Run each notebook top-to-bottom.
4. Follow the exercise cells to extend the examples.
5. Keep the official PowerShell documentation open while you work, especially for module and Azure cmdlet details.
