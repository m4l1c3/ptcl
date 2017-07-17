# Pen test checklist

> Is this a known application?
> Have you run ssl scan?
> Can you login?
  > does the app give you indication that a user/password is wrong, can you brute it?
>Is there open registration?
>Is there a search bar?
> Which pages are dynamic?
> CSRF?
> Is the login form vulnerable?
> Are there upload forms?
> Have you run burp's spider?
> Have you run nmap
> Is there a search function?
> XSS?
  >reflected or stored
> SQLi

## Once you have root - post privesc

> Check cron if its a linux system, see what scheduled tasks run
