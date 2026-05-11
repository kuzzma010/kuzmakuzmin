# Kuzma Kuzmin

Minimal static personal website for `kuzmakuzmin.com`.

## Project Structure

```text
.
├── index.html
├── assets/
│   └── hero.png
├── vercel.json
├── .gitattributes
└── .gitignore
```

## Local Preview

Open `index.html` directly in a browser, or run a local static server:

```bash
python -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

## Deploy To Vercel

1. Create a new GitHub repository.
2. Upload or push this project to the repository.
3. In Vercel, choose `Add New...` -> `Project`.
4. Import the GitHub repository.
5. Leave the framework preset as `Other`.
6. Leave build settings empty:
   - Build Command: empty
   - Output Directory: empty
   - Install Command: empty
7. Deploy.

## Connect Domain

In Vercel project settings:

1. Open `Settings` -> `Domains`.
2. Add `kuzmakuzmin.com`.
3. Add `www.kuzmakuzmin.com` if needed.
4. Follow the DNS records Vercel shows for your domain registrar.

Typical Vercel DNS setup:

```text
A      @      76.76.21.21
CNAME  www    cname.vercel-dns.com
```

Use the exact values from Vercel if they differ.

