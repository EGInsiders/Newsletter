---
ID: 317
post_title: Resetting your Password
author: Jon Morganeg
post_excerpt: ""
layout: post
permalink: >
  http://eduguideinsiders.shepherdhistory.org/2017/10/05/resetting-your-password/
published: true
post_date: 2017-10-05 15:28:19
---
<h1>Resetting your Password</h1>
If you find that you are having trouble remembering your account password, you can ask for a password reminder. While you are on the login page click on “Forgot password” underneath the login button. You will be taken to a new page where you are prompted to enter in the email address that you use when you log into your account. After submitting your email address, you will be sent an email message with a link. When you click on the link, you will be taken to a page where you can enter in a new password.
<h2>Testing Script</h2>
<img title="" src="http://eduguideinsiders.shepherdhistory.org/wp-content/uploads/2017/10/null-4.png" alt="" width="624" height="332" />

#Click Forgot Password

Given that I am on the Login screen

When I click on “Forgot Password”

Then I am taken to the password reset page

<img title="" src="http://eduguideinsiders.shepherdhistory.org/wp-content/uploads/2017/10/null-5.png" alt="" width="624" height="332" />

#Submit account email address

Given that I am on the “Reset Your Password” page

When I enter “<a href="mailto:eduguidepfl@gmail.com">eduguidepfl@gmail.com</a>”

And click “Reset Password”

Then a notification is sent to my inbox

And the page shows confirmation message “An email has been sent to <a href="mailto:eduguidepfl@gmail.com">eduguidepfl@gmail.com</a>.”

#Use Link in email to reset password

<img title="" src="http://eduguideinsiders.shepherdhistory.org/wp-content/uploads/2017/10/null-6.png" alt="" width="624" height="336" />

Given that I am viewing the password reset notification

When I click on the supplied link

Then I am taken to the site

And prompted to enter in a new password

And is logged in