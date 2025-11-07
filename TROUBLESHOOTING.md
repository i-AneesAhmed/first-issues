## 🧰 Troubleshooting

This document contains a list of **known issues** and **tips to fix them** during setup or usage.

---

### ⚠️ Issue: `JSON object must be str, not 'bytes'`

**Cause:**  
This error usually occurs when using an **incorrect Python version**.  
It happens because the `json` module in Python 3.6+ expects a string (`str`) object, not a `bytes` object.

**Fix:**  
✅ Make sure you are running the project with **Python 3.6 or higher**.  
You can check your version by running:

```bash
python --version
