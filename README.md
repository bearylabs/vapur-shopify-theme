# Vapur Shopify Theme

Custom Shopify theme based on the **Dawn** reference theme.

This theme serves as the foundation for the Vapur storefront and extends the functionality and design of Shopify’s official Dawn theme.

## Base Theme

This project is built on top of **Shopify Dawn**, Shopify's official reference theme for Online Store 2.0.

Dawn is optimized for performance, accessibility, and flexibility.
This repository customizes and extends Dawn for project-specific requirements.

Original repository:
https://github.com/Shopify/dawn

---

# Requirements

Before working with this theme, install:

* Node.js (LTS recommended)
* Shopify CLI
* Git

Install Shopify CLI:

```
npm install -g @shopify/cli @shopify/theme
```

Login to Shopify:

```
shopify login
```

---

# Development

Run a local development server connected to a Shopify store.

```
shopify theme dev
```

This will:

* upload the theme to your development store
* start a local development server
* enable hot reload when files change

---

# Project Structure

```
.
├── assets/        # CSS, JS, images
├── config/        # theme settings
├── layout/        # theme layout files
├── locales/       # translations
├── sections/      # dynamic Shopify sections
├── snippets/      # reusable components
├── templates/     # page templates
```

---

# Deployment

To push changes to a Shopify store:

```
shopify theme push
```

To pull the current theme from a store:

```
shopify theme pull
```

---

# Version Control

This repository tracks only the theme source code.
Store-specific configuration and content live inside Shopify and are **not version controlled**.

Recommended workflow:

1. Develop locally
2. Test using `shopify theme dev`
3. Push to the store when ready

---

# Customization

All custom modifications should be clearly separated from upstream Dawn logic whenever possible to make updates easier.

Typical customizations include:

* UI and branding changes
* additional sections
* custom Liquid logic
* JavaScript enhancements

---

# License

This theme is based on **Shopify Dawn**, which is released under the MIT license.

Any additional code in this repository follows the same license unless stated otherwise.
