# VXML
Voice XML scripts for Cisco voice routers

<h2>Common</h2> <br>
5-digit internal numbers, starts from <b>1</b> (11111 -- secretary) <br>
4-digit number is webex, starts from <b>4</b> <br>
Cisco Call Manager controls internal phones. <br>

<b>hello.wav</b> -- audio hello-message (greeting, the company name, instructions for further actions) <br>
<b>wrong_number.wav</b> -- a dialling number is wrong <br>
<b>busy_number.wav</b> -- a dialling number is busy <br>
<b>empty.wav</b> -- nobody picks up the phone (a person is absent) <br>

<h2>hello-transfer.vxml</h2> <br>
Simplest answerphone. It plays hello-message and tranfer a call to the internal phone.

<h2>menu.vxml</h2> <br>
It plays hello-message, offers to dial an internal number or wait a secretary answer. <br>
Transfers internal numbers to Call Manager.




