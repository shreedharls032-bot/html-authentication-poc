# HTML Authentication POC

This is a simple HTML-only authentication flow proof of concept.

## Pages Included

- login.html
- register.html
- forgot-password.html
- reset-password.html
- dashboard.html

## Flow Structure

Login → Dashboard  
Register → Login  
Forgot Password → Reset Password → Login  
Dashboard → Logout → Login  

## Notes

- No CSS used
- No JavaScript used
- Redirections handled using anchor tags only
- Pure HTML structure