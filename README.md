# BD Remittance Calculator

A fast, open-source calculator for money sent to Bangladesh (BDT) from any currency — EUR, USD, GBP, RON, SAR, AED and 160+ more. It fetches live exchange rates, works in both directions, and automatically includes the 2.5% Bangladesh Government Incentive.

**Live Demo:** [https://mogdho.github.io/remit-bd/](https://mogdho.github.io/remit-bd/)

### 🚀 Core Features

* **Any Currency to BDT:** Choose your send currency from the list; popular remittance currencies are at the top. Your choice is remembered.
* **Live Exchange Rates:** The latest rate to BDT is fetched automatically (ExchangeRate API). You can also type your own rate.
* **Incentive Calculation:** Computes the 2.5% government incentive for legal remittance channels.
* **Two Modes:** Switch between "how much TK should arrive" and "how much I'm sending".
* **Quick Amounts:** One-tap cards for common amounts — tap to copy the result.
* **Responsive Dark UI:** Works on desktop and mobile.
* **Zero Dependencies:** A single static page with no backend or build step.

### 🛠️ Tech Stack

* HTML5
* CSS3 (Vanilla, CSS Variables, Custom Animations)
* JavaScript (ES6+, Fetch API, Async/Await)

### 💻 Run Locally

No build tools are needed.

```bash
git clone https://github.com/mogdho/remit-bd.git
cd remit-bd
python -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080). You can also open `index.html` directly in a browser.

---

### 👨‍💻 Author
**Mogdho Paul**
