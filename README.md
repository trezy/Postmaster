# Postmaster

Postmaster will be a standalone email client built on NodeJS. The goal is to create a fully functional email client (think Gmail, Hotmail, Yahoo Mail, etc) with all the functionality of current popular mail clients, including support for SMTP, POP, and IMAP, as well as a few *new* features... 

## The problem

The state of rich email is dismal to say the least. Creating emails that are anything more than plain text is nothing short of painful. Developers must use tables, inline CSS, and ancient attributes to achieve the designs they want. Content must account for the quirks of all of the different email clients which are plentiful. To sum it all up, writing HTML emails sucks. The web has moved way past the use of these archaic methods but email clients have been left in the dust.

## The solution

My goal with Postmaster is to remove that necessity. While Postmaster should be able to render emails written in the current dismal ecosystem of email, it will also enable email to be sent with a new header - `theFutureIsHere`:copyright: (subject to change). This header will tell Postmaster that there is a beautiful, modern version of the code for this email and to render it with the best, most modern technologies available. Eventually I'd even likle to add limited Javascript support.

## The goal

I'll be developing Postmaster as a standalone client to be installed on any server with NodeJS. If all goes well Postmaster may growe up to become it's own service but I'm not really thinking that far ahead. The main goal is to show off what email *could* be if we ripped email clients out of the mud of the olden days and set them on the shiny new silver earth that we live in today.
