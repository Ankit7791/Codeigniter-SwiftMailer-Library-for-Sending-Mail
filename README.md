# Codeigniter-SwiftMailer-Library-for-Sending-Mail
Small Library code for sending Emails using PHP Codeigniter Framework Using SwiftMailer Library

1] Place the file Directly in libraries Folder in Codeigniter
   Custom_email.php

2] Add the $autoload['libraries'] = array('custom_email') in autoload.php 

3] Use in Controller using $this->custom_email->sendMail($emailsubject,$dataMessage, $usermail);

4] Also Download the swiftmailer library https://swiftmailer.symfony.com/ and place the hole folder in libraries section

5] Where you want to use this Custom_email class donot forget to include or use require on TOP  
   require_once APPPATH.'libraries/Swift-mailer/swift_required.php'; 
