# 🧭 Price Tracker Landing Page — Step-by-Step for Complete Beginners

## 🎯 Goal
Create a simple landing page on GitHub Pages to test the idea of **“Price Tracker for Bol.com Sellers”** and collect first emails via Formspree.

---

## 🔹 Step 1. Create a GitHub Repository
1. Go to 👉 [https://github.com/new](https://github.com/new)
2. Name it:
   ```
   price-tracker-landing
   ```
3. Check **Add a README file**
4. Click **Create repository**

---

## 🔹 Step 2. Create a Simple Web Page
1. In your repo, click **Add file → Create new file**
2. Name it:
   ```
   index.html
   ```
3. Paste this code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Price Tracker for Bol.com Sellers</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; padding: 40px; }
    h1 { color: #004aad; }
    p { max-width: 600px; margin: 10px auto; }
    button { background: #007bff; color: white; padding: 10px 20px; border: none; border-radius: 6px; cursor: pointer; }
    button:hover { background: #0056b3; }
  </style>
</head>
<body>
  <h1>Monitor Competitor Prices on Bol.com Automatically</h1>
  <p>Get daily price updates from your competitors — no coding, no setup. Perfect for dropshippers and Bol.com sellers.</p>
  <p>🚀 Try our beta and get 7 days free.</p>
  <form action="https://formspree.io/f/your_form_id" method="POST">
    <input type="email" name="email" placeholder="Enter your email" required style="padding:8px;width:250px">
    <button type="submit">Join Beta</button>
  </form>
</body>
</html>
```

4. Scroll down and click **Commit changes**.

---

## 🔹 Step 3. Turn on GitHub Pages
1. Go to **Settings → Pages**
2. Under **Build and deployment → Sourc
