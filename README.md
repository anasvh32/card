پروژه Weather Card

نقش فایل‌ها
- pyproject.toml: شناسنامه پروژه. اسم، نسخه پایتون و لیست پکیج‌ها.
- uv.lock: نسخه دقیق پکیج‌ها را قفل می‌کند.
- .python-version: نسخه پایتون مورد نیاز.
- .venv: محیط مجازی که پکیج‌ها در آن نصب می‌شوند.

بازسازی .venv
اگر پوشه .venv پاک شود، دستور uv run دوباره از روی uv.lock می‌سازدش.

تنظیم VS Code
با Ctrl+Shift+P برو، بزن Python: Select Interpreter و مسیر .venv را انتخاب کن. خطای Import حل می‌شود.