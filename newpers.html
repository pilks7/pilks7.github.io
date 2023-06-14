<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
  // Validate input data
  $name = sanitizeInput($_POST["Name"]);
  $email = sanitizeInput($_POST["Email"]);
  $message = sanitizeInput($_POST["Message"]);

  if (empty($name) || empty($email) || empty($message)) {
    echo "Please fill in all the fields.";
    exit;
  }

  if (!filter_var($email, FILTER_VALIDATE_EMAIL)) {
    echo "Invalid email address.";
    exit;
  }

  // Prepare email
  $to = "lukepilkington@hotmail.co.uk";
  $subject = "New Message from $name";
  $body = "Name: $name\nEmail: $email\n\n$message";

  // Send email
  $headers = "From: $email\r\n";

  if (mail($to, $subject, $body, $headers)) {
    echo "Message sent successfully.";
  } else {
    echo "Error occurred. Please try again later.";
  }
}

function sanitizeInput($input) {
  $input = trim($input);
  $input = stripslashes($input);
  $input = htmlspecialchars($input);
  return $input;
}
?>