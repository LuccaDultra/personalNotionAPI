# personalNotionAPI

# Personal Redirector

This repository serves as a simple and predictable **link redirector** system that I created for personal use.

## Purpose

Each folder in this repository is named after a unique **code** corresponding to an item I track in my personal inventory system. When I visit:

```
https://<my-github-username>.github.io/estoque/<code>
```

I am automatically redirected to a private, unrelated URL (such as a Notion page) that contains detailed information about the item.

## How It Works

- The **code** (which is the folder name) acts as a key to a hidden destination URL.
- The destination URLs are private and only accessible to me.
- This setup allows me to use a short, predictable URL to access complex or private links quickly and easily.
- It functions as a personal lightweight API for quick access without exposing any sensitive information.

## Privacy and Security

- The repository is public, but all sensitive destination URLs remain private as they are only stored within the redirect HTML files.
- The codes do not reveal any private details by themselves.
- This system is designed strictly for personal productivity and inventory management.

## Usage

- To add a new redirect, create a new folder named after the desired code.
- Add an `index.html` file inside with a redirect to the corresponding private URL.
- Push changes to keep the system updated and accessible.
