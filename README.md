# go-31 private module
Depends on github.com/octiq-nonexistent-org/private-auth. GitHub answers a missing or private repo the same way (asks for credentials), so this simulates a private dependency without needing one.
For a real private repo, point the require at a private repo of your own that the Octiq token cannot read.
Expected: clear auth/access error; no token or credentials in logs.
