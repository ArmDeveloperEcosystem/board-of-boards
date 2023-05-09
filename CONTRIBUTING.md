# Contributing

## Submitting a new board

1. Create a directory under `./boards/` for the manufacturer, if one doesn't already exist
2. Create a copy of `./boards/template.md` into the manufacturer's directory, naming the new file after the board you are adding.
3. Fill in the relevant board information. Copy directly from the board manufacturer's specification whenever possible.
4. Add links at the top of the board's page to the ARM IP the board uses, and any use cases you feel the board is ideally suited for.
5. Add links back to your board's page in the matching files in both `./ip/` and `./use-cases/`
6. Create a PR in Github with your new board and changes to IP and use case files. Please limit PRs to a single board unless you are submitted a family of closely related boards all together.


## Recommendations

- Make board files for specific devices rather than families of devices. 
  - For example, make a file for `NVIDIA Jetson Orin Nano` instead of all `NVIDIA Jetson` or even `NVIDIA Jetson Orin`.
- Don't add new use case files to `./use-cases/` without first discussing it with us in [Discord](https://discord.gg/armsoftwaredev), we want to keep this list short and driven by what our users are searching for
- Do add new ARM IP files to `./ip/` as needed, these are added as-needed to avoid having empty files.