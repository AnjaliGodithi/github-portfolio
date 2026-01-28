# Lab 01 Troubleshooting Notes

## Issue: git push permission denied / 403
**Cause:** Stored GitHub credentials were incorrect on this computer.

**Fix (Windows):**
1. Open Credential Manager
2. Windows Credentials
3. Remove `git:https://github.com`
4. Re-run `git push` and authenticate using a Personal Access Token (PAT)

