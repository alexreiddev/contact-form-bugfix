# Contact Form Bug Fix

A documented before/after fix for the most 
common HTML contact form bugs found on 
business websites.

---

## Bugs Fixed

### Bug 1 — Input Fields Missing name Attribute
**Symptom:** Form submits but no data arrives  
**Cause:** Inputs without name attributes are 
ignored by the browser on submission  
**Fix:** Added name attribute to every field

### Bug 2 — Wrong Input Type for Email
**Symptom:** Invalid emails accepted, 
no mobile keyboard optimization  
**Cause:** type="text" used instead of 
type="email"  
**Fix:** Changed to type="email" for 
validation and mobile UX

### Bug 3 — No Required Field Validation
**Symptom:** Empty form submits successfully  
**Cause:** No validation logic present  
**Fix:** JavaScript validation checks all 
fields before allowing submission

### Bug 4 — No User Feedback
**Symptom:** User has no idea if form 
worked or failed  
**Cause:** No success or error messages  
**Fix:** Added inline error messages and 
success confirmation

### Bug 5 — Empty Form Action
**Symptom:** Form submits to wrong URL  
**Cause:** action="" submits back to same page  
**Fix:** Proper action endpoint + method="POST"

### Bug 6 — No Email Format Validation
**Symptom:** Accepts "notanemail" as valid  
**Cause:** No regex validation on email field  
**Fix:** Regex pattern validates proper 
email format

---

## Skills Demonstrated
- HTML form structure best practices
- JavaScript form validation
- User experience error handling
- Email regex validation
- CSS form styling

---

## Contact
Available for bug fixing on Fiverr and Upwork.
