---
ID: 317
post_title: Resetting your Password
author: Jon Morganeg
post_excerpt: ""
layout: post
permalink: >
  http://eduguideinsiders.shepherdhistory.org/?p=317
published: false
---
<h1>Resetting your Password</h1>
<p></p>
<p>If you find that you are having trouble remembering your account password, you can ask for a password reminder. While you are on the login page click on “Forgot password” underneath the login button. You will be taken to a new page where you are prompted to enter in the email address that you use when you log into your account. After submitting your email address, you will be sent an email message with a link. When you click on the link, you will be taken to a page where you can enter in a new password.</p>
<p></p>
<h2>Testing Script</h2>
<p><img src="http://eduguideinsiders.shepherdhistory.org/wp-content/uploads/2017/10/null-4.png" width="624" height="332" alt="" title=""></p>
<p></p>
<p>#Click Forgot Password</p>
<p></p>
<p>Given that I am on the Login screen</p>
<p>When I click on “Forgot Password”</p>
<p>Then I am taken to the password reset page</p>
<p></p>
<p></p>
<p><img src="http://eduguideinsiders.shepherdhistory.org/wp-content/uploads/2017/10/null-5.png" width="624" height="332" alt="" title=""></p>
<p></p>
<p>#Submit account email address</p>
<p></p>
<p>Given that I am on the “Reset Your Password” page</p>
<p>When I enter “<a href="mailto:eduguidepfl@gmail.com">eduguidepfl@gmail.com</a>”</p>
<p>And click “Reset Password”</p>
<p>Then a notification is sent to my inbox</p>
<p>And the page shows confirmation message “An email has been sent to <a href="mailto:eduguidepfl@gmail.com">eduguidepfl@gmail.com</a>.”</p>
<p></p>
<p>#Use Link in email to reset password</p>
<p></p>
<p><img src="http://eduguideinsiders.shepherdhistory.org/wp-content/uploads/2017/10/null-6.png" width="624" height="336" alt="" title="">
</p>
<p>Given that I am viewing the password reset notification</p>
<p>When I click on the supplied link</p>
<p>Then I am taken to the site</p>
<p>And prompted to enter in a new password</p>
<p>And is logged in</p>
<p></p>
<p></p>