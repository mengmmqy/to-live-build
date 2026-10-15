# To Live — Windows builds

This public repository only stores the Windows build workflow. The application source remains at [Gitee](https://gitee.com/hao_ziyi/to-live).

1. Open [Actions → Build Windows installer](https://github.com/mengmmqy/to-live-build/actions/workflows/windows.yml).
2. Click **Run workflow**.
3. When the run succeeds, download **To-Live-Windows-x64-number** from its Artifacts section. It contains the `.exe` installer, application ZIP, checksums and verification report.

Artifacts are retained for **1 day**. Every run fetches the latest Gitee main and records the exact source commit. Standard public-repository Windows runners are free; artifact storage remains subject to account quotas. No Release publication or paid larger runner is configured.

The canonical workflow file is maintained in the Gitee source repository at `.github/workflows/windows.yml`. Updating application code only requires pushing Gitee; updating the workflow itself requires copying that file here.
