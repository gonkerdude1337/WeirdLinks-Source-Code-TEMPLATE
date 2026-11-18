# WeirdLinks-Source-Code-TEMPLATE
Repository for the WeirdLinks source code, modified to be YOUR own template for doing YOUR own sites.
---

# WEIRDLINKS
> "Definetively a WEIRD site for WEIRD people."

Weirdlinks is a simple imageboard/forum i made when i was bored, still up to this day.
---

## FUNCTIONALITIES

- Functional Feed
- Anti-Impostor Tripcode(use a secret password to generate a tripcode)
- Admin Mode Login(Allows you to login as admin and delete unwanted posts)
- Replies/Mentions(Mention a post/Reply to a post using its ID)
- Personalization(Basic profile personalization)
- Cookie-Based Memory
---

### TECHNOLOGIES USED

- PHP(Backend/Logic)
- MySQL/MySQLi(Data Bank)
- HTML/Native CSS(Appearance)
---

#### HOW TO RUN IT LOCALLY

1. Clone/Download the repository(i think you know how to do that).
2. Create a MySQL data bank(ex: weirdlinks_db)
3. Configure the connection
  Change the variables $server, $user, $pass and $bank to something like this:
    ```bash
    $server = "localhost";
    $user = "your_user";
    $pass = "your_password";
    $bank = "weirdlinks_db";
    ```
4. Put your administrator password
   ```bash
   $admin_password [
     "your_admin_password_here!!!"
   ];
   ```
5. Start the server(put the files onto a folder like XAMPP's htdocs and access http://localhost/WeirdLinks or something like that)
---
Thats everything i had to type for now.

Author - arthur_sales9/gonkerdude1337

Warn me about any bug or upgrade i should do! And you can send me suggestions too!

This code is from the WeirdLinks version 1.2
