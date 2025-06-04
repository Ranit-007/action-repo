# action-repo

✅ Step 1: clone the repo to you machine.

✅ Step 2: add your file

```bash
echo "final test" > test_final.txt
git add .
git commit -m "Final test after webhook fix"
git push
```
Webhook gets sent

Flask saves it

UI shows new message

✅ Step 3: now in your localhost:5000 you shall see the output like
```bash
Ranit-007 pushed to main on June 3, 2025 at 6:02 PM
```
