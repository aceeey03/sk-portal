# SK Web — City of Ligao

Official Sangguniang Kabataan Web System for the City of Ligao, Albay.

## Files

| File | Description |
|------|-------------|
| `index.html` | Redirects to the SK Mini Portal |
| `sk-admin-v8.html` | SK Admin System (officers only) |
| `sk-portal-v3.html` | SK Public Mini Portal |
| `CNAME` | Custom domain config for GitHub Pages |

## Setup

1. Upload all `.html` files to this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Under **Custom domain**, enter your domain (e.g. `sk-ligao.gov.ph`)
5. Check **Enforce HTTPS**

## Custom Domain DNS Records

Point your domain registrar to GitHub Pages using these DNS records:

### Option A — Apex domain (sk-ligao.gov.ph)
```
Type: A    Name: @    Value: 185.199.108.153
Type: A    Name: @    Value: 185.199.109.153
Type: A    Name: @    Value: 185.199.110.153
Type: A    Name: @    Value: 185.199.111.153
Type: AAAA Name: @    Value: 2606:50c0:8000::153
Type: AAAA Name: @    Value: 2606:50c0:8001::153
Type: AAAA Name: @    Value: 2606:50c0:8002::153
Type: AAAA Name: @    Value: 2606:50c0:8003::153
```

### Option B — Subdomain (www.sk-ligao.gov.ph or portal.sk-ligao.gov.ph)
```
Type: CNAME    Name: www (or portal)    Value: YOUR-GITHUB-USERNAME.github.io
```

## Contact
SK City of Ligao, Albay — Philippines
