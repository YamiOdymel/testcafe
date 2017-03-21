# TestCafe with Firefox + Chromium

Files

* `.drone.yml` - The CI configure file, just like `.travis.yml`.
* `script.sh` - The startup script.
* `test.js` - The test file for TestCafe.

Command

```bash
testcafe 'chromium --no-sandbox --headless --disable-gpu,firefox' test.js
```

Output

```bash
Running tests in:
 - Chrome 56.0.2924 / Linux 0.0.0
 - Firefox 45.0.0 / Linux 0.0.0
 Example page
 ✓ Emulate user actions and perform a verification
 1 passed (3s)
```
