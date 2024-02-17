# Lab 1 - HTML Injection

Welcome to Lab 1 of the HTML Injection series at Hactify! This lab will introduce you to HTML Injection, a vulnerability commonly found in web applications.

## About HTML Injection
HTML Injection is a vulnerability that occurs in web applications, allowing users to insert HTML code via a specific parameter or entry point. Unlike Cross-site Scripting (XSS), HTML Injection only allows the injection of certain HTML tags. When an application fails to properly handle user-supplied data, attackers can inject valid HTML code, typically via a parameter value, to insert their own content into the page.

### Severity
- The severity of HTML Injection is categorized as a P4 bug with a CVSS score of 0.1-3.9, which is Low. However, in cases of account takeover, it can be categorized as P3.

### Exploiting HTML Injection
1. Test every entry point on a target website.
2. Refer to the HTML Injection Documentation.
3. Check for valid HTML Injection onto the screen.

## Getting Started
To begin Lab 1:
1. Navigate to the Hactify Labs website: [https://labs.hacktify.in](https://labs.hacktify.in).
2. Find the HTML Labs section.
3. Select Lab 1 - HTML Injection.
   ![Lab 1](lab1intro.png)
4. Read the lab description and instructions provided.
5. Click on the "Start Lab" button to begin.

## Let's Get Exploring
Alright, time to dive in! Here's what we're gonna do:
1. Check if Our Name Shows Up: Type your name into the search bar and hit enter. Notice how your name pops up on the page? Yeah, that's what we're talking about!
   ![Lab 1](searchkenzie.png)
2. Let's Have Some Fun with HTML: Now, let's get a bit sneaky. Try typing in `<h1>kenzie</h1>` into the search bar. What happens? Oh, looks like something interesting happened! Take a peek:
   ![Lab 1](htmlkenzie.png)

   This confirms that the search parameter is vulnerable to HTML injection.

