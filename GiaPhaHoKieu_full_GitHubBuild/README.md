# Gia Pha Họ Kiều — GitHub Build Package

Upload all files to a new GitHub repo `GiaPhaHoKieu` and push to `main`. The workflow will build an NSIS installer and upload it as an artifact.
Steps:
1. Create repo and upload files (commit to main).
2. Wait for Actions run; download artifact `GiaPhaHoKieu_Setup` from Actions -> run -> Artifacts.
3. Run the installer on Windows.
