# Connecting chainedevolution.com to the New Site

Hey! This sounds scarier than it is. You're basically just updating two settings on your domain account. Takes 5 minutes. I'll walk you through it.

---

## First — where did you buy the domain?

Find which one applies to you and skip straight to that section:

- [I bought it on GoDaddy](#godaddy)
- [I bought it on Namecheap](#namecheap)
- [I bought it on Google Domains or Squarespace](#google-domains--squarespace)
- [I'm not sure / something else](#not-sure-which-one)

---

## GoDaddy

1. Go to **godaddy.com** and log in
2. Click your name in the top right → click **"My Products"**
3. Find **chainedevolution.com** in the list → click **"DNS"** next to it
4. You'll see a table of records. Look for any row where the **Type** column says **"A"** and the **Name** column says **"@"** — click the pencil/edit icon on that row
5. Change the **Value** field to: `76.76.21.21`
6. Click **Save**
7. Now look for a row where **Type** says **"CNAME"** and **Name** says **"www"** — click edit on that one
8. Change the **Value** field to: `cname.vercel-dns.com`
9. Click **Save**
10. **Text Leland and let him know you're done** — he'll flip the switch on his end

---

## Namecheap

1. Go to **namecheap.com** and log in
2. Click **"Domain List"** on the left sidebar
3. Find **chainedevolution.com** → click **"Manage"**
4. Click the **"Advanced DNS"** tab at the top
5. Look for a row with **Type: A Record** and **Host: @** → click the edit icon (pencil)
6. Change the **Value** to: `76.76.21.21` → click the green checkmark to save
7. Look for a row with **Type: CNAME Record** and **Host: www** → click edit
8. Change the **Value** to: `cname.vercel-dns.com` → save
9. **Text Leland and let him know you're done**

---

## Google Domains / Squarespace

1. Go to **domains.google.com** (or **squarespace.com** → Domains) and log in
2. Click on **chainedevolution.com**
3. Click **"DNS"** in the left menu
4. Scroll down to **"Custom Records"**
5. Find the **A** record with host **@** → click edit → change the value to `76.76.21.21` → save
6. Find the **CNAME** record with host **www** → click edit → change the value to `cname.vercel-dns.com` → save
7. **Text Leland and let him know you're done**

---

## Not sure which one?

1. Go to **whois.domaintools.com**
2. Type in `chainedevolution.com` and hit search
3. Look for **"Registrar"** in the results — that's where it was bought
4. Log into that website and follow the steps above (they're all pretty similar)
5. Still stuck? Screenshot what you're looking at and send it to Leland

---

## What happens after?

- Once you text Leland, he'll add the domain on his end (takes 2 minutes)
- The new site usually goes live within **30–60 minutes**
- Sometimes it takes up to 24 hours — that's normal, not broken
- Your old site stays up the whole time during the switch, so nothing breaks

---

## Something looks different than described?

Every registrar moves stuff around. If your screen doesn't match exactly, look for anything that says **DNS**, **Name Servers**, or **DNS Records** and poke around in there. You're looking for two things:

- A record called **A** pointing to **@**
- A record called **CNAME** pointing to **www**

When in doubt, screenshot it and send it to Leland.
