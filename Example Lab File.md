# Creating and Linking a GPO – Step by Step

## 🎯 Objective
Create a GPO to disable Control Panel for domain users.

---

## ✅ Step 1: Open GPMC
1. Login to Domain Controller
2. Open Start → Group Policy Management

---

## ✅ Step 2: Create GPO
1. Expand Forest → Domains → yourdomain.local
2. Right-click → Create a GPO in this domain, and Link it here
3. Name: Disable_Control_Panel

---

## ✅ Step 3: Edit GPO
1. Right-click GPO → Edit
2. Navigate to:
   User Configuration → Policies → Administrative Templates → Control Panel
3. Enable: Prohibit access to Control Panel and PC Settings

---

## ✅ Step 4: Apply GPO
On client:

```
gpupdate /force
```

## ✅ Step 5: Verify
On client:
```
gpresult /r
```

# Try opening Control Panel – access should be denied.

---

## 🧠 Explanation
This GPO enforces user-level restrictions from the Domain Controller, ensuring policy compliance across all domain-joined machines.

## Author
Name - Saiyed Alisha




